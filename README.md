# ParaphraseSorceCode



Run: python SmallestLevenshteinPairs.py 1.cpp 2.cpp 3.cpp 

Output:
OneBigTest/1.cpp OneBigTest/2.cpp
File1 -> File2 found (229) most simular lines 
File2 -> File1 found (111) most simular lines 
Number of shared pairs: 38
OneBigTest/1.cpp OneBigTest/3.cpp
File1 -> File2 found (229) most simular lines 
File2 -> File1 found (86) most simular lines 
Number of shared pairs: 42
OneBigTest/2.cpp OneBigTest/3.cpp
File1 -> File2 found (111) most simular lines 
File2 -> File1 found (86) most simular lines 
Number of shared pairs: 43
======
Original Line of Sorce Code:
using namespace std;
Is Most Similar to:
string s = parts[i];
======
======
Original Line of Sorce Code:
typedef long long int64;//NOTES:int64
Is Most Similar to:
map < long long, int > dp[12];
======
======
Original Line of Sorce Code:
typedef unsigned long long uint64;//NOTES:uint64
Is Most Similar to:
typedef unsigned long long ull;
======
======
Original Line of Sorce Code:
#define contain(S,X) (((S)&two(X))!=0)//NOTES:contain(
Is Most Similar to:
#define forn(i, n) for(int i = 0; i < (int)(n); i++)
======
======
Original Line of Sorce Code:
int toInt(string s){int r=0;istringstream sin(s);sin>>r;return r;}//NOTES:toInt(
Is Most Similar to:
#define forit(i, s) for(__typeof(s.begin()) i = s.begin(); i != s.end(); i++)
======
======
Original Line of Sorce Code:
const int MODE=10009;
Is Most Similar to:
p[3] = 1000000000;
======
======
Original Line of Sorce Code:
int m,n;
Is Most Similar to:
int k, n;
======
======
Original Line of Sorce Code:
int C[maxn][26];
Is Most Similar to:
int tmp[26];
======
======
Original Line of Sorce Code:
pair<ipair,ipair> Q0[10000000];
Is Most Similar to:
vector < pair <int, int> > poly;
======
======
Original Line of Sorce Code:
for (k=0;1;k++)
Is Most Similar to:
forit(j, dp[i])
======
======
Original Line of Sorce Code:
for (int set2=1;set2<two(4);set2++)
Is Most Similar to:
for (int tt = 1; tt <= tn; tt++)
======
======
Original Line of Sorce Code:
for (int i=0;i<n;i++)
Is Most Similar to:
for (int i = 0; i < n; i++)
======
======
Original Line of Sorce Code:
for (int i=0;i<n;i++)
Is Most Similar to:
for (int i = 0; i < n; i++)
======
======
Original Line of Sorce Code:
int a2=a,b2=b,c2=c;
Is Most Similar to:
int c = j->second;
======
======
Original Line of Sorce Code:
if (cnt>=1) a2+=D[i][0];
Is Most Similar to:
res = res * 1000 + v[i];
======
======
Original Line of Sorce Code:
sort(Q1,Q1+S1);
Is Most Similar to:
parts.pb(curr);
======
======
Original Line of Sorce Code:
for (int i=0;i<S1;i++)
Is Most Similar to:
for (int i = 0; i < 5; i++)
======
======
Original Line of Sorce Code:
Q0[S0++]=Q1[i];
Is Most Similar to:
curr += s[i];
======
======
Original Line of Sorce Code:
multiply=(multiply*E[p])%MODE;
Is Most Similar to:
sort(poly.begin(), poly.end());
======
======
Original Line of Sorce Code:
R[k]=(R[k]+multiply*d%MODE)%MODE;
Is Most Similar to:
v[y] = u[y] + dic[x][poly[y].second];
======
======
Original Line of Sorce Code:
for (int i=1;i<MODE;i++)
Is Most Similar to:
for (int i = 1; i <= k; i++)
======
======
Original Line of Sorce Code:
inv[i]=(x%MODE+MODE)%MODE;
Is Most Similar to:
u[i] = x % 1000, x /= 1000;
======
======
Original Line of Sorce Code:
for (int i=0;i<maxk;i++)
Is Most Similar to:
for (int i = 0; i <= k; i++)
======
======
Original Line of Sorce Code:
FA[i]=(i==0)?1:(FA[i-1]*i)%MODE;
Is Most Similar to:
ans[i] = (ans[i] + add * c) % mod;
======
======
Original Line of Sorce Code:
for (int caseId=1;caseId<=testcase;caseId++)
Is Most Similar to:
for (int i = 0; i < (int)parts.size(); i++)
======
======
Original Line of Sorce Code:
printf("Case #%d:",caseId);
Is Most Similar to:
printf("Case #%d:", tt);
======
======
Original Line of Sorce Code:
scanf("%d",&n);
Is Most Similar to:
scanf("%d", &tn);
======
======
Original Line of Sorce Code:
memset(C,0,sizeof(C));
Is Most Similar to:
memset(tmp, 0, sizeof(tmp));
======
======
Original Line of Sorce Code:
for (int i=0;i<n;i++)
Is Most Similar to:
for (int i = 0; i < n; i++)
======
======
Original Line of Sorce Code:
scanf("%s",str);
Is Most Similar to:
scanf("%s", _s);
======
======
Original Line of Sorce Code:
C[i][str[j]-'a']++;
Is Most Similar to:
dic[i][curr[j] - 'a']++;
======
======
Original Line of Sorce Code:
for (int i=0;i<maxk;i++)
Is Most Similar to:
for (int i = 0; i <= k; i++)
======
======
Original Line of Sorce Code:
for (string s;sin>>s;)
Is Most Similar to:
vector <string> parts;
======
======
Original Line of Sorce Code:
B[c++]=1;
Is Most Similar to:
p[0] = 1;
======
======
Original Line of Sorce Code:
B[c-1]++;
Is Most Similar to:
s += "+";
======
======
Original Line of Sorce Code:
for (int i=0;i<n;i++)
Is Most Similar to:
for (int i = 0; i < n; i++)
======
======
Original Line of Sorce Code:
if (c==4)
Is Most Similar to:
if (i == k)
======
======
Original Line of Sorce Code:
return 0;
Is Most Similar to:
return res;
======
======
Original Line of Sorce Code:
#include <iomanip>
Is Most Similar to:
#include <complex>
======
======
Original Line of Sorce Code:
#include <cstdio>
Is Most Similar to:
#include <stdio.h>
======
======
Original Line of Sorce Code:
#include <cmath>
Is Most Similar to:
#include <math.h>
======
======
Original Line of Sorce Code:
#include <cstdlib>
Is Most Similar to:
#include <stdlib.h>
======
======
Original Line of Sorce Code:
#include <cctype>
Is Most Similar to:
#include <ctype.h>
======
======
Original Line of Sorce Code:
#include <string>
Is Most Similar to:
#include <string.h>
======
======
Original Line of Sorce Code:
#include <cstdio>
Is Most Similar to:
#include <stdio.h>
======
======
Original Line of Sorce Code:
#include <cmath>
Is Most Similar to:
#include <math.h>
======
======
Original Line of Sorce Code:
#include <cstdlib>
Is Most Similar to:
#include <stdlib.h>
======
======
Original Line of Sorce Code:
typedef pair<int,int> ipair;//NOTES:ipair
Is Most Similar to:
typedef pair<short, int> PCI;
======
======
Original Line of Sorce Code:
const int MODE=10009;
Is Most Similar to:
const int MOD = 10009;
======
======
Original Line of Sorce Code:
int m,n;
Is Most Similar to:
int k, n;
======
======
Original Line of Sorce Code:
int C[maxn][26];
Is Most Similar to:
int wcnt[20][26];
======
======
Original Line of Sorce Code:
int R[maxk],D[maxn][4];
Is Most Similar to:
cnt[i] += wcnt[cur][i];
======
======
Original Line of Sorce Code:
int PN[maxk];
Is Most Similar to:
int perm[6];
======
======
Original Line of Sorce Code:
int S0,S1;
Is Most Similar to:
int v = 1;
======
======
Original Line of Sorce Code:
void DFS(int set,int multiply,int depth)
Is Most Similar to:
memcpy(cnt, save_cnt, sizeof(int) * 26);
======
======
Original Line of Sorce Code:
if (set==0)
Is Most Similar to:
if (cur == n)
======
======
Original Line of Sorce Code:
for (int set2=1;set2<two(4);set2++)
Is Most Similar to:
for (int scen=1; scen<=tc; ++scen) {
======
======
Original Line of Sorce Code:
for (int i=0;i<n;i++)
Is Most Similar to:
for (int i=0; i<k; ++i)
======
======
Original Line of Sorce Code:
if (contain(set2,s))
Is Most Similar to:
if (poly[i] == '+') {
======
======
Original Line of Sorce Code:
G=(G*D[i][s])%MODE;
Is Most Similar to:
v = (v * cnt[j]) % MOD;
======
======
Original Line of Sorce Code:
DFS(set-set2,G,depth+1);
Is Most Similar to:
typedef vector<int> VI;
======
======
Original Line of Sorce Code:
for (int k=1;k<=m;k++)
Is Most Similar to:
for (int i=1; i<=5; ++i)
======
======
Original Line of Sorce Code:
for (int i=0;i<n;i++)
Is Most Similar to:
for (int i=0; i<k; ++i)
======
======
Original Line of Sorce Code:
Q1[S1++]=MP(MP(a2,b2),MP(c2,d));
Is Most Similar to:
sol[c-1] += eval() * (perm[c] / div);
======
======
Original Line of Sorce Code:
sort(Q1,Q1+S1);
Is Most Similar to:
sol[c-1] %= MOD;
======
======
Original Line of Sorce Code:
for (int i=0;i<S1;i++)
Is Most Similar to:
for (int i=0; i<26; ++i)
======
======
Original Line of Sorce Code:
int E[3];
Is Most Similar to:
int sol[5];
======
======
Original Line of Sorce Code:
int main()
Is Most Similar to:
int main() {
======
======
Original Line of Sorce Code:
int testcase;
Is Most Similar to:
int res = 0;
======
======
Original Line of Sorce Code:
printf("Case #%d:",caseId);
Is Most Similar to:
printf("Case #%d:", scen);
======
======
Original Line of Sorce Code:
scanf("%d",&m);
Is Most Similar to:
scanf("%d", &tc);
======
======
Original Line of Sorce Code:
memset(C,0,sizeof(C));
Is Most Similar to:
memset(sol, 0, sizeof(int) * k);
======
======
Original Line of Sorce Code:
for (int i=0;i<n;i++)
Is Most Similar to:
for (int i=0; i<k; ++i)
======
======
Original Line of Sorce Code:
for (int j=0;str[j];j++)
Is Most Similar to:
for (int j=0; word[j]; ++j)
======
======
Original Line of Sorce Code:
C[i][str[j]-'a']++;
Is Most Similar to:
wcnt[i][word[j]-'a']++;
======
======
Original Line of Sorce Code:
for (int i=0;line[i];i++) if (line[i]=='+') line[i]=' ';
Is Most Similar to:
void backtrack(int cur, int c, int div, bool was_zero) {
======
======
Original Line of Sorce Code:
for (int i=0;i<n;i++)
Is Most Similar to:
for (int i=0; i<k; ++i)
======
======
Original Line of Sorce Code:
DFS(two(c)-1,1,0);
Is Most Similar to:
char word[1000];
======
======
Original Line of Sorce Code:
printf("\n");
Is Most Similar to:
puts("");
======
======
Original Line of Sorce Code:
fflush(stdout);
Is Most Similar to:
p.push_back(t);
======
======
Original Line of Sorce Code:
#include <cstdio>
Is Most Similar to:
#include <stdio.h>
======
======
Original Line of Sorce Code:
#include <string>
Is Most Similar to:
#include <string.h>
======
======
Original Line of Sorce Code:
#include <cassert>
Is Most Similar to:
#include <assert.h>
======
======
Original Line of Sorce Code:
#include <ctime>
Is Most Similar to:
#include <queue>
======
======
Original Line of Sorce Code:
#include <cstdlib>
Is Most Similar to:
#include <stdlib.h>
======
======
Original Line of Sorce Code:
#include <cmath>
Is Most Similar to:
#include <math.h>
======
======
Original Line of Sorce Code:
#define forn(i, n) for(int i = 0; i < (int)(n); i++)
Is Most Similar to:
void backtrack(int cur, int c, int div, bool was_zero) {
======
======
Original Line of Sorce Code:
#define sz(v)((v).size())
Is Most Similar to:
if (c > 0 && !was_zero) {
======
======
Original Line of Sorce Code:
typedef long long ll;
Is Most Similar to:
typedef set<int> SI;
======
======
Original Line of Sorce Code:
typedef unsigned long long ull;
Is Most Similar to:
typedef pair<short, int> PCI;
======
======
Original Line of Sorce Code:
typedef long double ldbl;
Is Most Similar to:
typedef complex<double> tComp;
======
======
Original Line of Sorce Code:
ll res = 0;
Is Most Similar to:
int res = 0;
======
======
Original Line of Sorce Code:
res = res * 1000 + v[i];
Is Most Similar to:
res = (res + v) % MOD;
======
======
Original Line of Sorce Code:
int main( void )
Is Most Similar to:
int main() {
======
======
Original Line of Sorce Code:
int tn;
Is Most Similar to:
int tc;
======
======
Original Line of Sorce Code:
scanf("%d", &tn);
Is Most Similar to:
scanf("%d", &tc);
======
======
Original Line of Sorce Code:
printf("Case #%d:", tt);
Is Most Similar to:
printf("Case #%d:", scen);
======
======
Original Line of Sorce Code:
char _s[1000];
Is Most Similar to:
char poly[1000];
======
======
Original Line of Sorce Code:
s += "+";
Is Most Similar to:
puts("");
======
======
Original Line of Sorce Code:
string curr;
Is Most Similar to:
struct term {
======
======
Original Line of Sorce Code:
for (int i = 0; i < (int)s.size(); i++)
Is Most Similar to:
for (int i=0; i<(int)p.size(); ++i) {
======
======
Original Line of Sorce Code:
if (s[i] == '+')
Is Most Similar to:
if (poly[i] == '+') {
======
======
Original Line of Sorce Code:
parts.pb(curr);
Is Most Similar to:
p.push_back(t);
======
======
Original Line of Sorce Code:
else
Is Most Similar to:
}t;
======
======
Original Line of Sorce Code:
p[0] = 1;
Is Most Similar to:
perm[0] = 1;
======
======
Original Line of Sorce Code:
int k, n;
Is Most Similar to:
int v = 1;
======
======
Original Line of Sorce Code:
scanf("%d%d", &k, &n);
Is Most Similar to:
scanf("%d %d", &k, &n);
======
======
Original Line of Sorce Code:
string curr;
Is Most Similar to:
struct term {
======
======
Original Line of Sorce Code:
memset(dic[i], 0, sizeof(dic[i]));
Is Most Similar to:
memset(t.cnt, 0, sizeof(int) * 26);
======
======
Original Line of Sorce Code:
dic[i][curr[j] - 'a']++;
Is Most Similar to:
wcnt[i][word[j]-'a']++;
======
======
Original Line of Sorce Code:
int tmp[26];
Is Most Similar to:
int cnt[26];
======
======
Original Line of Sorce Code:
memset(tmp, 0, sizeof(tmp));
Is Most Similar to:
memset(sol, 0, sizeof(int) * k);
======
======
Original Line of Sorce Code:
for (int i = 0; i < (int)s.size(); i++)
Is Most Similar to:
for (int i=0; i<(int)p.size(); ++i) {
======
======
Original Line of Sorce Code:
tmp[s[i] - 'a']++;
Is Most Similar to:
t.cnt[poly[i]-'a']++;
======
======
Original Line of Sorce Code:
for (int i = 0; i < 26; i++)
Is Most Similar to:
for (int i=0; i<26; ++i)
======
======
Original Line of Sorce Code:
poly.pb(mp(tmp[i], i));
Is Most Similar to:
perm[i] = perm[i-1] * i;
======
======
Original Line of Sorce Code:
dp[i].clear();
Is Most Similar to:
p.clear();
======
======
Original Line of Sorce Code:
cerr << "k = " << i << " " << dp[i].size();
Is Most Similar to:
backtrack(cur + 1, c + x, div * perm[x], x == 0);
======
======
Original Line of Sorce Code:
long long add = 1;
Is Most Similar to:
const int MOD = 10009;
======
======
Original Line of Sorce Code:
add = (add * u[x]) % mod;
Is Most Similar to:
v = (v * cnt[j]) % MOD;
======
======
Original Line of Sorce Code:
ans[i] = (ans[i] + add * c) % mod;
Is Most Similar to:
sol[c-1] += eval() * (perm[c] / div);
======
======
Original Line of Sorce Code:
if (i == k)
Is Most Similar to:
if (cur == n)
======
======
Original Line of Sorce Code:
return 0;
Is Most Similar to:
return;
======
1  =>  using namespace std;
1  =>  string s = parts[i];
1  =>  typedef long long int64;//NOTES:int64
1  =>  map < long long, int > dp[12];
1  =>  typedef unsigned long long uint64;//NOTES:uint64
2  =>  typedef unsigned long long ull;
1  =>  #define contain(S,X) (((S)&two(X))!=0)//NOTES:contain(
2  =>  #define forn(i, n) for(int i = 0; i < (int)(n); i++)
1  =>  int toInt(string s){int r=0;istringstream sin(s);sin>>r;return r;}//NOTES:toInt(
1  =>  #define forit(i, s) for(__typeof(s.begin()) i = s.begin(); i != s.end(); i++)
2  =>  const int MODE=10009;
1  =>  p[3] = 1000000000;
2  =>  int m,n;
3  =>  int k, n;
2  =>  int C[maxn][26];
2  =>  int tmp[26];
1  =>  pair<ipair,ipair> Q0[10000000];
1  =>  vector < pair <int, int> > poly;
1  =>  for (k=0;1;k++)
1  =>  forit(j, dp[i])
2  =>  for (int set2=1;set2<two(4);set2++)
1  =>  for (int tt = 1; tt <= tn; tt++)
8  =>  for (int i=0;i<n;i++)
4  =>  for (int i = 0; i < n; i++)
1  =>  int a2=a,b2=b,c2=c;
1  =>  int c = j->second;
1  =>  if (cnt>=1) a2+=D[i][0];
2  =>  res = res * 1000 + v[i];
2  =>  sort(Q1,Q1+S1);
2  =>  parts.pb(curr);
2  =>  for (int i=0;i<S1;i++)
1  =>  for (int i = 0; i < 5; i++)
1  =>  Q0[S0++]=Q1[i];
1  =>  curr += s[i];
1  =>  multiply=(multiply*E[p])%MODE;
1  =>  sort(poly.begin(), poly.end());
1  =>  R[k]=(R[k]+multiply*d%MODE)%MODE;
1  =>  v[y] = u[y] + dic[x][poly[y].second];
1  =>  for (int i=1;i<MODE;i++)
1  =>  for (int i = 1; i <= k; i++)
1  =>  inv[i]=(x%MODE+MODE)%MODE;
1  =>  u[i] = x % 1000, x /= 1000;
2  =>  for (int i=0;i<maxk;i++)
2  =>  for (int i = 0; i <= k; i++)
1  =>  FA[i]=(i==0)?1:(FA[i-1]*i)%MODE;
2  =>  ans[i] = (ans[i] + add * c) % mod;
1  =>  for (int caseId=1;caseId<=testcase;caseId++)
1  =>  for (int i = 0; i < (int)parts.size(); i++)
2  =>  printf("Case #%d:",caseId);
2  =>  printf("Case #%d:", tt);
1  =>  scanf("%d",&n);
2  =>  scanf("%d", &tn);
2  =>  memset(C,0,sizeof(C));
2  =>  memset(tmp, 0, sizeof(tmp));
1  =>  scanf("%s",str);
1  =>  scanf("%s", _s);
2  =>  C[i][str[j]-'a']++;
2  =>  dic[i][curr[j] - 'a']++;
1  =>  for (string s;sin>>s;)
1  =>  vector <string> parts;
1  =>  B[c++]=1;
2  =>  p[0] = 1;
1  =>  B[c-1]++;
2  =>  s += "+";
1  =>  if (c==4)
2  =>  if (i == k)
2  =>  return 0;
1  =>  return res;
1  =>  #include <iomanip>
1  =>  #include <complex>
3  =>  #include <cstdio>
3  =>  #include <stdio.h>
3  =>  #include <cmath>
3  =>  #include <math.h>
3  =>  #include <cstdlib>
3  =>  #include <stdlib.h>
1  =>  #include <cctype>
1  =>  #include <ctype.h>
2  =>  #include <string>
2  =>  #include <string.h>
1  =>  typedef pair<int,int> ipair;//NOTES:ipair
2  =>  typedef pair<short, int> PCI;
2  =>  const int MOD = 10009;
1  =>  int wcnt[20][26];
1  =>  int R[maxk],D[maxn][4];
1  =>  cnt[i] += wcnt[cur][i];
1  =>  int PN[maxk];
1  =>  int perm[6];
1  =>  int S0,S1;
2  =>  int v = 1;
1  =>  void DFS(int set,int multiply,int depth)
1  =>  memcpy(cnt, save_cnt, sizeof(int) * 26);
1  =>  if (set==0)
2  =>  if (cur == n)
1  =>  for (int scen=1; scen<=tc; ++scen) {
4  =>  for (int i=0; i<k; ++i)
1  =>  if (contain(set2,s))
2  =>  if (poly[i] == '+') {
1  =>  G=(G*D[i][s])%MODE;
2  =>  v = (v * cnt[j]) % MOD;
1  =>  DFS(set-set2,G,depth+1);
1  =>  typedef vector<int> VI;
1  =>  for (int k=1;k<=m;k++)
1  =>  for (int i=1; i<=5; ++i)
1  =>  Q1[S1++]=MP(MP(a2,b2),MP(c2,d));
2  =>  sol[c-1] += eval() * (perm[c] / div);
1  =>  sol[c-1] %= MOD;
2  =>  for (int i=0; i<26; ++i)
1  =>  int E[3];
1  =>  int sol[5];
1  =>  int main()
2  =>  int main() {
1  =>  int testcase;
2  =>  int res = 0;
2  =>  printf("Case #%d:", scen);
1  =>  scanf("%d",&m);
2  =>  scanf("%d", &tc);
2  =>  memset(sol, 0, sizeof(int) * k);
1  =>  for (int j=0;str[j];j++)
1  =>  for (int j=0; word[j]; ++j)
2  =>  wcnt[i][word[j]-'a']++;
1  =>  for (int i=0;line[i];i++) if (line[i]=='+') line[i]=' ';
2  =>  void backtrack(int cur, int c, int div, bool was_zero) {
1  =>  DFS(two(c)-1,1,0);
1  =>  char word[1000];
1  =>  printf("\n");
2  =>  puts("");
1  =>  fflush(stdout);
2  =>  p.push_back(t);
1  =>  #include <cassert>
1  =>  #include <assert.h>
1  =>  #include <ctime>
1  =>  #include <queue>
1  =>  #define sz(v)((v).size())
1  =>  if (c > 0 && !was_zero) {
1  =>  typedef long long ll;
1  =>  typedef set<int> SI;
1  =>  typedef long double ldbl;
1  =>  typedef complex<double> tComp;
1  =>  ll res = 0;
1  =>  res = (res + v) % MOD;
1  =>  int main( void )
1  =>  int tn;
1  =>  int tc;
1  =>  char _s[1000];
1  =>  char poly[1000];
2  =>  string curr;
2  =>  struct term {
2  =>  for (int i = 0; i < (int)s.size(); i++)
2  =>  for (int i=0; i<(int)p.size(); ++i) {
1  =>  if (s[i] == '+')
1  =>  else
1  =>  }t;
1  =>  perm[0] = 1;
1  =>  scanf("%d%d", &k, &n);
1  =>  scanf("%d %d", &k, &n);
1  =>  memset(dic[i], 0, sizeof(dic[i]));
1  =>  memset(t.cnt, 0, sizeof(int) * 26);
1  =>  int cnt[26];
1  =>  tmp[s[i] - 'a']++;
1  =>  t.cnt[poly[i]-'a']++;
1  =>  for (int i = 0; i < 26; i++)
1  =>  poly.pb(mp(tmp[i], i));
1  =>  perm[i] = perm[i-1] * i;
1  =>  dp[i].clear();
1  =>  p.clear();
1  =>  cerr << "k = " << i << " " << dp[i].size();
1  =>  backtrack(cur + 1, c + x, div * perm[x], x == 0);
1  =>  long long add = 1;
1  =>  add = (add * u[x]) % mod;
1  =>  return;
