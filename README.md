### C++ Template to make life easier
---

```cpp
#include <bits/stdc++.h>
using namespace std;

template <typename... T>
void read(T &...args) {
    ((cin >> args), ...);
}

#define rep(a, b) for(int i = a; i < b; ++i)
#define ll long long int

void solve()
{
	int t;
	cin >> t;
	while(t--) {
		//Function code
	}
}

int main()
{
	ios_base::sync_with_stdio(0);
   	cin.tie(0); cout.tie(0);
	
	solve();    
	return 0;
}
