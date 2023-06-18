# Quick Merge Sort
Unstable comparison sort for bidirectional iterators in O(n log n) time &amp; O(1) space

# Get Started
```cpp
#include "quick_merge_sort.h++"
#include <iostream>
#include <vector>

int main(){
    vector<int> a{5,6,3,2,3,54,234,5,52,5,52512};
    qmsort::quick_merge_sort(a.begin(), a.end());
    for(auto p: a) cout<<p<<" ";
    return 0;
}
```
