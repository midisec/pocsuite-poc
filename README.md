# pocsuite-poc
基于pocsuite3框架的poc和exp，持续更新不同漏洞的验证代码。

---

## POC列表

欢迎小伙伴一起编写，欢迎issues~

注：本poc仅提供漏洞验证功能，请在授权情况下进行渗透测试。对未授权目标的测试本库不承担责任，均由使用者本人自行承担。

[poc编写规范及说明要求](https://github.com/knownsec/pocsuite3/blob/master/docs/CODING.md)

### 常见CMS

| 序号 | poc_name                                                     | description                                         |
| ---- | ------------------------------------------------------------ | --------------------------------------------------- |
| 1    | [zbzcms_file_deletion.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/yccms3.4_file_deletion.py) | 南宁比优网络科技有限公司 站帮主CMS 2.1 任意文件删除 |
| 2    | [zbzcms_admin_getshell.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/zbzcms_admin_getshell.py) | 南宁比优网络科技有限公司 站帮主CMS 2.1 后台getshell |
| 3    | [yccms3.4_remote_pass_change.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/yccms3.4_remote_pass_change.py) | YCCMS3.4 任意管理员密码重置漏洞                     |
| 4    | [yccms3.4_file_upload.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/yccms3.4_file_upload.py) | YCCMS3.4 后台存在多个文件上传漏洞导致getshell       |
| 5    | [yccms3.4_file_deletion.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/yccms3.4_file_deletion.py) | YCCMS3.4 存在任意文件删除                           |
| 6    | [74cms_rce.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/74cms_rce.py) | 骑士cms6.0.48及以下 前台RCE getshell                |
| 7    | [dedecms5.7.85_admin_getshell.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/dedecms5.7.85_admin_getshell.py) | dedecms5.7.85 后台getshell                          |
|      |                                                              |                                                     |

### 2022HW

| 序号 | poc_name                                                     | description                                      | 时间       |
| ---- | ------------------------------------------------------------ | ------------------------------------------------ | ---------- |
| 1    | [trx_behaviorsystem_rce.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/trx_behaviorsystem_rce.py) | 天融信上网行为管理系统static_convert.php命令执行 | 2022/07/28 |
| 2    | [yongyou_ksoa_upload_rce.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/yongyou_ksoa_upload_rce.py) | 用友时空KSOA前台文件上传漏洞导致rce              | 2022/07/28 |
| 3    | [mingyu_login_bypass.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/mingyu_login_bypass.py) | 安恒信息-明御WAF存在登陆绕过漏洞                 | 2022/07/29 |
| 4    | [landray_oa_rce.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/landray_oa_rce.py) | 蓝凌OA-未授权命令执行漏洞(无回显)                | 2022/08/02 |
| 5    | [nsfocus_firewall_upload.py](https://github.com/midisec/pocsuite-poc/blob/main/pocs/nsfocus_firewall_upload.py) | 绿盟-下一代防火墙resourse.php任意文件上传漏洞    | 2022/08/04 |
|      |                                                              |                                                  |            |



---

## 参考

[pocsuite3](https://github.com/knownsec/pocsuite3)