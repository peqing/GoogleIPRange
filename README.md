# GoogleIPRange
整合自以下gogo tester、checkgoogleip、gscan等的IP库
* [https://github.com/azzvx/gogotester/blob/2.3/GoGo%20Tester/Resources/InnerIpSet.txt](https://github.com/azzvx/gogotester/blob/2.3/GoGo%20Tester/Resources/InnerIpSet.txt)
* [https://github.com/moonshawdo/checkgoogleip/blob/master/checkip.py](https://github.com/moonshawdo/checkgoogleip/blob/master/checkip.py)
* [https://github.com/yinqiwen/gscan/blob/master/iprange.conf](https://github.com/yinqiwen/gscan/blob/master/iprange.conf)
* [https://github.com/yinqiwen/gscan/blob/master/example/iprange.conf](https://github.com/yinqiwen/gscan/blob/master/example/iprange.conf)
* [https://github.com/yinqiwen/gscan/blob/master/example/huge_iprange.conf](https://github.com/yinqiwen/gscan/blob/master/example/huge_iprange.conf)

另补了一些根据ASN反查得来的Google/Youtube IP段，全部转成了CIDR格式。
不足/24条件的也以/24处理了，故存在误差。

##建议使用[CheckGoogleIP](https://github.com/moonshawdo/checkgoogleip/)，快速且结果精准。
使用说明：https://github.com/CNMan/GoogleIPRange/wiki/CheckGoogleIP

gogo tester可用来处理ip_tmpok.txt，导出goagent需要的带|格式。

##批量PING可用[PingInfoView](http://www.nirsoft.net/utils/multiple_ping_tool.html)。

##需要补充请直接提交[Pull Requset](https://github.com/lenovo-me/GoogleIPRange/pulls)。
