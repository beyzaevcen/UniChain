# UniChain
<img width="800" alt="Ekran Resmi 2024-01-25 18 51 22" src="https://github.com/zehraozturkk/UniChain/assets/95762073/2fcd271e-3ba9-4615-b88a-44862123b3ac">

## Introduction
[en:]
Blockchain technology is not just the technology of the future; it's the technology of today. As online payments become widespread, transparency in daily activities, such as food orders, becomes increasingly important. Despite its reliability, blockchain technology is not as widely used as it could be. UniChain seeks to seize the opportunity to popularize blockchain, starting with young people.

Integrating blockchain technology into university cafeteria systems addresses a common issue faced by universities. This solution aims to popularize blockchain by ensuring transparency in food purchases and providing a convenient and secure payment process using tokens. UniChain envisions overcoming challenges in current cafeteria systems, reducing the risk of lost money, and promoting blockchain use among university students.

# Cafeteria System Challenges and Solutions

## Systemic Slowdowns Caused by Centralization

### Challenge:
The centralization of cafeteria systems introduces challenges related to systemic slowdowns, impacting the overall efficiency and responsiveness of the system.

### Solution:
Implementing a decentralized architecture for the cafeteria system can alleviate systemic slowdowns. Distributing transaction processing and data management across multiple nodes can enhance system performance during peak hours.

---

## Security Challenges Arising from Intermediary Banks

### Challenge:
The involvement of intermediary banks in cafeteria transactions raises security concerns, posing potential risks to the integrity of sensitive financial information.

### Solution:
To address security challenges, consider implementing end-to-end encryption and utilizing secure channels for financial transactions. Minimizing reliance on intermediary banks and adopting blockchain technology may enhance the overall security posture of the cafeteria system.

---

## Limitations in Fund Transfer Among Students

### Challenge:
In the current cafeteria system, students face limitations in transferring funds to peers, restricting the flexibility and usability of the money stored within the system.

### Solution:
Enable a peer-to-peer fund transfer feature within the cafeteria system. Implementing a secure and user-friendly mechanism for students to transfer funds directly to each other can enhance the overall versatility and usability of the monetary resources within the system.

---

These proposed solutions aim to address the identified challenges in the cafeteria system. However, it's essential to carefully assess and tailor these solutions based on the specific requirements and constraints of the system in use.



This is our project model overview:


<img width="600" alt="" src="https://github.com/zehraozturkk/UniChain/assets/101568897/ac251356-b07e-4471-a77f-c537f713a149">


## Technologies We Used

<img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="HTML" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/w3_css/w3_css-icon.svg" alt="CSS" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/javascript/javascript-icon.svg" alt="JavaScript" width="40" height="40"/> <img src="https://docs.soliditylang.org/en/latest/_static/img/logo.svg" alt="Solidity" width="40" height="40"/> <img src="https://trufflesuite.com/assets/logo.png" alt="Truffle" width="40" height="40"/> <img src="https://seeklogo.com/images/G/ganache-logo-1EB72084A8-seeklogo.com.png" alt="Ganache" width="40" height="40"/> <img src="https://logowik.com/content/uploads/images/metamask-fox-icon-in-flat-style2194.logowik.com.webp" alt="MetaMask" width="40" height="40"/>

  


- **HTML, CSS:** Design of the user interface.

- **JavaScript:** Development of the user interface and calling smart contracts.

- **Solidity:** Writing smart contracts.

- **Truffle:** Compiling and migrating smart contracts.

- **Ganache:** Local blockchain for testing purposes.

- **MetaMask:** Browser extension for interacting with the Ethereum blockchain.



## Instructions for Running this Project

1. Clone and open the codes.

2. Use Ganache to create a test account. Download Ganache and run the following code to see your accounts and information:

    ```
    ganache-cli
    ```

3. Open your MetaMask and add another account connected to your Ganache account for testing.

4. Connect MetaMask to our webpage for token operations. Click the "CONNECT METAMASK" button on our webpage.

5. Deploy your contract using Truffle. Before that, install Truffle:

    ```
    npm install -g truffle
    ```

6. After the installation, run this command:

    ```
    truffle deploy
    ```

7. After deployment, you'll see the contract address in your terminal. Take this address and the ABI and paste them into your `main.js`.

8. Now, with the correct address and ABI, you can use your contract's functions. Click the "Reservation" button on our webpage, and when prompted by MetaMask, grant permission for the operation.


  
</p>

# Thank You

Get ready to explore the benefits of blockchain technology using the UniChain project. For more assistance or questions, please feel free to contact our support team.

**Project Team:**
- Nermin Beyzanur Evcen  
  Email: beyzaevceen@gmail.com

- Fatmatüzzehra Öztürk  
  Email: fzehraozturk34@gmail.com

As the UniChain team, we wish you a secure, transparent, and user-friendly experience!

---

# UniChain Projesi

## Tanıtım
[tr:]
Blockchain teknolojisi sadece geleceğin teknolojisi değil, bugünün teknolojisidir. Online ödemelerin yaygınlaşması ile günlük aktivitelerde, özellikle yemek siparişlerinde şeffaflık giderek daha önemli hale gelmektedir. Ancak, güvenilir olmasına rağmen blockchain teknolojisi, yaygın olarak kullanılmamaktadır. UniChain, bu fırsatı gençlerle başlayarak blockchain'i popülerleştirmeyi hedeflemektedir.

Blockchain teknolojisini üniversite yemekhane sistemlerine entegre etmek, üniversitelerin karşılaştığı ortak bir sorunu ele almaktadır. Bu çözüm, gıda alımlarında şeffaflığı sağlayarak ve token kullanarak kullanıcılar için güvenli ve uygun bir ödeme süreci sunarak blockchain'i popülerleştirmeyi amaçlamaktadır. UniChain, mevcut yemekhane sistemlerindeki zorlukları aşmayı, kayıp paraların riskini azaltmayı ve üniversite öğrencileri arasında blockchain kullanımını teşvik etmeyi hedeflemektedir.

# Yemekhane Sistemi Zorlukları ve Çözüm Önerileri

## Merkeziyetin Neden Olduğu Sistemsel Yavaşlamalar

### Sorun:
Yemekhane sistemlerinin merkeziyeti, sistem genelinde yavaşlamalara neden olan zorlukları beraberinde getirir, bu da sistem genelindeki verimliliği ve tepkisel hızı etkiler.

### Çözüm:
Yemekhane sistemi için merkeziyetten uzak bir mimari uygulamak, sistemsel yavaşlamaları hafifletebilir. İşlemleri ve veri yönetimini birden fazla noktaya yaymak, yoğun saatlerde sistem performansını artırabilir.

---

## Aracı Bankalardan Kaynaklanan Güvenlik Zorlukları

### Sorun:
Yemekhane işlemlerinde aracı bankaların rol alması, hassas finansal bilgilerin bütünlüğüne yönelik güvenlik endişelerine neden olur.

### Çözüm:
Güvenlik zorluklarına çözüm olarak, işlemler için uçtan uca şifreleme uygulamak ve finansal işlemler için güvenli kanalları kullanmak önemlidir. Aracı bankalara olan bağımlılığı azaltmak ve blockchain teknolojisini benimsemek, yemekhane sisteminin genel güvenlik düzeyini artırabilir.

---

## Öğrenciler Arasındaki Fon Transferindeki Kısıtlamalar

### Sorun:
Mevcut yemekhane sistemlerinde öğrenciler, paralarını birbirlerine transfer etmede kısıtlamalarla karşılaşırlar, bu da sistem içindeki para kullanımının esnekliğini ve kullanılabilirliğini sınırlar.

### Çözüm:
Yemekhane sistemi içinde öğrenciden öğrenciye para transferini sağlayacak bir özellik etkinleştirmek çözüm olabilir. Öğrencilere, paralarını doğrudan birbirlerine transfer etme olanağı sağlamak, sistem içindeki parasal kaynakların genel kullanılabilirliğini ve kullanışlılığını artırabilir.

---

Bu önerilen çözüm stratejileri, yemekhane sistemlerinde tespit edilen sorunlara çözüm getirmeyi amaçlamaktadır. Ancak, bu çözümlerin sistem üzerindeki spesifik gereksinimlere ve kısıtlamalara dikkatlice değerlendirilerek uyarlanması önemlidir.


## Proje Modeli İncelemesi:
<img width="600" alt="" src="https://github.com/zehraozturkk/UniChain/assets/101568897/ac251356-b07e-4471-a77f-c537f713a149">


## Kullandığımız Teknolojiler

<img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="HTML" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/w3_css/w3_css-icon.svg" alt="CSS" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/javascript/javascript-icon.svg" alt="JavaScript" width="40" height="40"/> <img src="https://docs.soliditylang.org/en/latest/_static/img/logo.svg" alt="Solidity" width="40" height="40"/> <img src="https://trufflesuite.com/assets/logo.png" alt="Truffle" width="40" height="40"/> <img src="https://seeklogo.com/images/G/ganache-logo-1EB72084A8-seeklogo.com.png" alt="Ganache" width="40" height="40"/> <img src="https://logowik.com/content/uploads/images/metamask-fox-icon-in-flat-style2194.logowik.com.webp" alt="MetaMask" width="40" height="40"/>

HTML, CSS: Kullanıcı arayüzünün tasarımı.

JavaScript: Kullanıcı arayüzünün geliştirilmesi ve akıllı sözleşmelerin çağrılması.

Solidity: Akıllı sözleşmelerin yazılması.

Truffle: Akıllı sözleşmelerin derlenmesi ve dağıtılması.

Ganache: Test amaçlı yerel blockchain.

MetaMask: Ethereum blockchain ile etkileşim için tarayıcı eklentisi.

## Projeyi Çalıştırma Talimatları

1. Kodları kopyalayın ve açın.

2. Test hesabı oluşturmak için Ganache kullanın. Ganache'i indirin ve aşağıdaki kodu çalıştırarak hesaplarınızı ve bilgilerinizi görüntüleyin:

    ```
    ganache-cli
    ```

3. MetaMask'ınızı açın ve test için Ganache hesabınıza bağlı başka bir hesap ekleyin.

4. Token işlemleri için MetaMask'ı web sitemize bağlayın. Web sitemizdeki "METAMASK'I BAĞLA" düğmesine tıklayın.

5. Akıllı sözleşmenizi Truffle kullanarak dağıtın. Önce Truffle'ı yükleyin:

    ```
    npm install -g truffle
    ```

6. Kurulumdan sonra bu komutu çalıştırın:

    ```
    truffle deploy
    ```

7. Dağıtımdan sonra, sözleşme adresini terminalinizde göreceksiniz. Bu adresi ve ABI'yi alın ve bunları `main.js` dosyanıza yapıştırın.

8. Artık doğru adres ve ABI ile sözleşmenizin fonksiyonlarını kullanabilirsiniz. Web sitemizdeki "Rezervasyon" düğmesine tıklayın ve MetaMask tarafından işlem için izin istendiğinde izin verin.


## Teşekkürler

UniChain projesini kullanarak, blockchain teknolojisinin avantajlarını keşfetmeye hazır olun. Daha fazla yardım veya soru için lütfen destek ekibimizle iletişime geçin.

**Proje Ekibi:**
- Nermin Beyzanur Evcen  
  Email: beyzaevceen@gmail.com

- Fatmatüzzehra Öztürk  
  Email: fzehraozturk34@gmail.com

UniChain ekibi olarak, güvenli, şeffaf ve kullanıcı dostu bir deneyim yaşamanızı dileriz!

