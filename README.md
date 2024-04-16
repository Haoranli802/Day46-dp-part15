# Day46-dp-part15

● 583. 两个字符串的删除操作 

if(s.charAt(i - 1) == t.charAt(j - 1) then dp[i][j] = dp[i - 1][j - 1]

else dp[i][j] = Math.max(dp[i - 1][j - 1] + 2, Math.max(dp[i - 1][j], dp[i][j - 1]) + 1);

也就是同时删除s和t或者只删除其中一个字符。



● 72. 编辑距离 


● 编辑距离总结篇   
