### methods

validRoleList 检测输入的玩家 ID(昵称)列表是否是合法的玩家列表 ——@/api/common.js

customMessage 对 element 的 Message 的二次封装, 全局混入 ——src/mixins/basePageOptions.js

customNotify 对 element 的 Notification 的二次封装, 全局混入 ——src/mixins/basePageOptions.js

parseTime_BASE 将时间戳(秒)转为 YYYY-MM-DD HH:mm:ss 的字符串格式 ——src/mixins/basePageOptions.js

returnParam_BASE 将参数对象转换为请求参数对象 ——src/mixins/basePageOptions.js

getDefaultTimeZone 获取默认时区(后台会返回默认时区) ——src/mixins/basePageOptions.js

getUTCTodayBeginAndEnd 获取 UTC 当天时间(功能页面如果默认当天, 使用此函数返回的时间), 全局混入 ——src/mixins/getTime.js

returnAssembledHtml 多个字段合并为一列展示, 全局混入 ——src/mixins/tableColumns.js

download_BASE 导出函数, 全局混入 ——src/mixins/download.js

returnNumberRangeParma_BASE 数值范围参数处理函数, 全局混入 ——src/mixins/requestParamConvert/index.js
