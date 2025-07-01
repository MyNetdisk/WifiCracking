<div align="left">

简体中文 | [English](https://github.com/MyNetdisk/WifiCracking/blob/main/README.md)

</div>

### 📌 项目简介

这是一个基于 Python 的图形化 WiFi 破解工具，使用 `pywifi` 模块控制无线网卡，通过密码字典爆破指定的 WiFi 网络。用户可扫描周围 WiFi，选择目标网络后导入密码字典进行自动尝试连接。

> ⚠️ **仅供学习和授权测试使用，禁止非法使用本工具！**

---

### 🛠️ 环境要求

* Python 3.6+
* Windows 操作系统
* 一张无线网卡
* 管理员权限运行脚本（访问网卡权限）

---

### 📦 安装依赖

```bash
pip install pywifi
pip install comtypes
```

或使用推荐的 `requirements.txt` 文件：

```bash
pip install -r requirements.txt
```

**requirements.txt 内容：**

```txt
pywifi>=1.1.11
comtypes>=1.1.10
```

---

### ▶️ 运行项目

```bash
python bruteForceWifi.py
```

---

### 📚 使用步骤

1. 点击【搜索附近WiFi】按钮扫描附近网络；
2. 双击 WiFi 列表中的目标项，自动填入 SSID；
3. 点击【添加密码文件目录】，选择你的密码字典文件（每行一个密码）；
4. 点击【开始破解】，程序会依次尝试密码；
5. 破解成功后会显示正确密码并弹出提示。

---

### 📂 密码字典示例

```txt
12345678
admin1234
qwertyuiop
```

---

### ❗注意事项

* 破解时间取决于字典大小；
* 网络环境需稳定；
* 不支持 WPA3；
* **请勿攻击非授权 WiFi 网络！**