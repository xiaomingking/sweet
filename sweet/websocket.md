INQUIRY_COUNTS  待接诊数发生变化   刷新左上角数字
INQUIRY_QUESTION_CHANGED 库中问题状态有变化 刷新接诊动态
INQUIRY_NEW_MESSAGE 刷新左侧用户列表  并判断当前聊天窗口的问题ID是否和传过来的一样  一样就刷新聊天窗口
INQUIRY_COUNTS  这个失效  用INQUIRY_QUESTION_CHANGED 替代
问诊动态已优化内容：
1、平均等待时间长短的处理 
2、回复时间为空不显示
3、问诊详情、问诊历史添加加载动画
接诊人员发布优化内容： 
  基本拖拽功能已实现，之后讨论优化其他细节