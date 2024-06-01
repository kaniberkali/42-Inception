![Docker_(container_engine)_logo](https://github.com/akaniber/Inception/assets/116187665/9709d565-62f3-4f5e-a6a4-111c6ec39116)

*Turkish and English source by akaniber*

- *Projede kullanılan terimler ve indirilen paketler güncelleme geldikçe değişiklik gösterebilir!*

# What is Docker?

Docker is a software platform designed to help developers build, share, and run modern applications. It allows you to package your application and its dependencies into a standardized unit called a container, which can be easily shared and run on any machine that has Docker installed.

# What is Container?

A container is a lightweight, standalone, executable package of software that includes everything needed to run an application. It consists of an entire runtime environment, including the application code, runtime, system tools, libraries, and settings. Containers are isolated from each other and from the host system, which makes them portable and easy to deploy across different environments.

------------

## Different VM's and Containers

The primary difference between containers and virtual machines is that containers provide a way to virtualize an OS so that the same code can run on any device, while virtual machines virtualize an entire machine down to the hardware layers. Containers are small, fast, and portable because they do not need to include a guest OS in every instance, while virtual machines require a full copy of the operating system for each instance.

### Downside of VMs

- Each vm needs a. full-blown OS
- Slow to start
- Resource intensive

### Advantages of Containers

- Allow running multiple apps in isolation
- Are lightweight process
- Use OS of the host
- Start quickly
- Need less hardware resources

![Docke-vs-VM](https://github.com/akaniber/Inception/assets/116187665/681bd258-243a-4f8d-aa31-00195b52aeb1)

# Docker nedir?

Docker, yazılım uygulamalarını geliştirmek, dağıtmak ve çalıştırmak için kullanılan bir platformdur. Docker, bir tür konteynerleme yazılımıdır. Konteynerler, bir uygulamanın tüm gereksinimlerini (kod, çalışma zamanı, sistem araçları, kütüphaneler ve ayarlar gibi) bir araya getirerek, bağımsız ve taşınabilir bir şekilde çalışmasını sağlar. Uygulamanızı ve bağımlılıklarını, Docker yüklü herhangi bir makinede kolayca paylaşılabilen ve çalıştırılabilen konteyner adı verilen standartlaştırılmış bir birimde paketlemenizi sağlar.

# Konteyner Nedir?

Konteyner, bir uygulamayı çalıştırmak için gereken her şeyi içeren hafif, bağımsız, çalıştırılabilir bir yazılım paketidir. Uygulama kodu, çalışma zamanı, sistem araçları, kütüphaneler ve ayarlar dahil olmak üzere tüm bir çalışma zamanı ortamından oluşur. Konteynerler birbirlerinden ve ana sistemden izole edilmiştir, bu da onları taşınabilir ve farklı ortamlara dağıtımı kolay hale getirir.

Docker konteynerleri, uygulamaların birbirleriyle ve konak işletim sistemiyle izole bir şekilde çalışmasına olanak tanır. Bu sayede, uygulamaların farklı ortamlarda (geliştirme, test, üretim) tutarlı bir şekilde çalışması sağlanır. Docker, hızlı dağıtım, ölçeklenebilirlik ve kaynak verimliliği gibi avantajlar sunar.

Docker container'lar, Docker Image'larından çalışan örneklerdir. Docker Image'ları, bir uygulamanın çalışması için gerekli olan tüm bileşenleri içeren bir şablon veya pakettir. Docker Image'ları, Dockerfile adı verilen metin dosyaları aracılığıyla tanımlanır ve Docker Daemon tarafından oluşturulur. Bir Docker Image'ı, çalıştırıldığında bir Docker container oluşturulur ve bu container'lar Docker Daemon tarafından yönetilir.

------------

## Sanal Makine ve Konteyner Farkı

Konteynerler ve sanal makineler arasındaki temel fark, konteynerlerin bir işletim sistemini sanallaştırmak için bir yol sunmasıdır, böylece aynı kod herhangi bir cihazda çalışabilirken, sanal makineler tüm bir makineyi donanım katmanlarına kadar sanallaştırır. Konteynerler küçük, hızlı ve taşınabilirdir çünkü her örnekte bir konuk işletim sistemi içermeleri gerekmezken, sanal makineler her örnek için işletim sisteminin tam bir kopyasını gerektirir.

### Sanal Makinelerin Dezavantajları

- Her vm'nin tam gelişmiş bir işletim sistemine ihtiyacı vardır
- Yavaş başlıyor
- Kaynak yoğun

### Konteynerlerin Avantajları

- Birden fazla uygulamayı tek başına çalıştırmaya izin verir
- Hafif süreçler işler
- Ana bilgisayarın işletim sistemini kullanın
- Hızlı başlıyor
- Daha az donanım kaynağına ihtiyaç duyar

