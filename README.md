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



---

## 参考

[pocsuite3](https://github.com/knownsec/pocsuite3)