#include <bits/stdc++.h>
using namespace std;
class Solution {
  public:
    long long seriesSum(int n) {
        long long j = 0;
        for (int i = 1; i <= n; i++) {
            j += i;
        }
        return j;
    }
};
int main() {
    int t;
    scanf("%d", &t);
    while (t--) {
        int n;
        scanf("%d", &n);
        Solution obj;
        long long res = obj.seriesSum(n);
        cout << res << endl;
    }
    return 0;
}

