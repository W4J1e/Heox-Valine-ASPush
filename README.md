# Heox-Valine-ASPush
## 说明
一个基于leancloud推送valine评论的项目  
原作者 小康 由于不再使用valine，不再维护该项目，故我接手来维护。  

2020.12.31新增说明：

由于valine本身的缺陷和Leancloud流控等原因，本人目前用有后端的waline评论系统取代了valine，且官方原生支持推送，部署在其它平台可以保障推送即时到达。详情请[戳这里](https://www.hin.cool/posts/waline.html)。

## 主要解决问题：

①因Qmsg酱接口地址更换，因此修改项目中相应的内容确保触发推送不再404；

②精简推送模板，内容更简洁。

## 将要做的TODO：

维护保障正常使用。

### 2020.12.26更新：
修复评论（不是回复）无法获取评论位置的问题，感谢@lewky 大佬。
