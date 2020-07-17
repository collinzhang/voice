# voice: 
Voice detected by microphone, designed by LabVIEW with itestgroup.com



即日起本软件版本由SVN管理

FCT_Voice：
SVN地址：（私有地址）
svn://gitee.com/itestgroup/FCT_Voice

https://github.com/collinzhang/voice.git

版本记录：

20191211-1: 增加Switch.vi，用于侦测按钮动作（高电平触发），放置于TestEnd，INI配置文件增加Switch的端口配置。
	工作模式：按钮具备防抖功能，保持住大约0.3秒，即300毫秒以上生效；FAIL时需按住红色按钮0.3秒以上夹具上升释放。

20191217-1:增加一个报告的路径，不再分日期独立建目录，测试结束后立即更新状态（此前为报告生成确认后再更新状态）。

Version: Domi_FCT_TS01_20191106-1


----Design Team: www.itestgroup.com----