# Backdoor Uygulaması

![Python](https://img.shields.io/badge/python-3.x-blue.svg)

Bu proje, test amaçları için oluşturulmuş basit bir backdoor uygulamasını içerir. Lütfen bu projeyi yalnızca etik sınırlar içinde kullanmayı unutmayın.

**UYARI:** Bu proje sadece test amacıyla hazırlanmıştır ve yasalara uygun olarak kullanılmalıdır. Geliştirici, projenin kötü niyetli veya yasa dışı amaçlarla kullanılmasından sorumlu değildir.

---

## Nasıl Kullanılır

1. Ana makinede (`listener.py`), hedef makinede (`socket.py`) bulunan Python dosyalarını indirin.
2. `listener.py` dosyasındaki IP adresini ve port numarasını güncelleyin.
3. Projeyi terminal veya komut istemcisinde çalıştırın:
   ```sh
   python listener.py
   python socket.py
---

**Hedef makine, komutları almak ve dosya aktarımları yapmak için kullanılır.**

## Gereksinimler
1. Python 3.x 
2. socket
3. base64
4. simplejson

**Lisans**  
Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için LİSANS dosyasına göz atabilirsiniz.

**UYARI**   
Bu proje yasal ve etik sınırlar içinde kullanılmalıdır. Geliştirici, projenin kötü niyetli veya yasa dışı kullanımı nedeniyle ortaya çıkabilecek sorunlardan sorumlu değildir.

**UYARI**   
Bu proje sadece test amaçlı olarak hazırlanmıştır. Yasaları ve etik kuralları ihlal etmemek önemlidir. Herhangi bir hedef makine üzerinde bu tür bir yazılımın kullanılması yasalara aykırı olabilir. Bu projenin kullanımı ve sonuçları tamamen kullanıcının sorumluluğundadır. Geliştirici, kötü niyetli veya yasa dışı kullanım nedeniyle ortaya çıkabilecek her türlü sorundan sorumlu değildir.

**----------------------------------------------------------------------------------------------------------------------------------------**
# Backdoor Application

![Python](https://img.shields.io/badge/python-3.x-blue.svg)

This project includes a simple backdoor application created for testing purposes. Please use this project within ethical boundaries.

**WARNING:** This project is intended for testing purposes only and should be used in compliance with the law. The developer is not responsible for any malicious or illegal use.

---

## How to Use

1. Download the Python files for the host machine (`listener.py`) and the target machine (`socket.py`).
2. Update the IP address and port number in the `listener.py` file.
3. Run the project in a terminal or command prompt:
   ```sh
   python listener.py
   python socket.py
---

**The target machine is used to receive commands and perform file transfers.**

## Requirements
1. Python 3.x
2. socket
3. base64
4. simplejson

**License**     
This project is licensed under the MIT License. For more information, please refer to the LICENSE file.

**WARNING**     
 This project should be used within legal and ethical boundaries. The developer is not responsible for any issues arising from malicious or illegal use.

**Warning**     
This project is created for testing purposes only. It is important to respect laws and ethical guidelines. Using such software on any target machine might be against the law. The usage and consequences of this project are entirely the responsibility of the user. The developer is not responsible for any issues that may arise due to malicious or illegal use.