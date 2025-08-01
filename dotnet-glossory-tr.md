| 🔹 Terim                       | 🧾 Türkçesi / Açıklama                                                                                                 |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| **Microservice**               | Mikroservis – Küçük, bağımsız olarak çalışan ve tek bir işlevi olan servis                                             |
| **Bounded Context**            | Sınırlı Bağlam – Her servisin kendi iş kurallarını ve veri modelini içeren bağımsız alanı                              |
| **API Gateway**                | API Geçidi – Tüm dış isteklerin geçtiği merkezî giriş noktası; yetkilendirme, yönlendirme gibi işlevleri vardır        |
| **Service Discovery**          | Servis Keşfi – Mikroservislerin birbirini dinamik olarak bulmasını sağlayan sistem                                     |
| **Resilience**                 | Dayanıklılık – Hatalara karşı sistemin ayakta kalabilme yeteneği (örneğin circuit breaker)                             |
| **Circuit Breaker**            | Devre Kesici – Hatalı servise yapılan istekleri geçici olarak engelleyerek sistemin geri kalanını korur                |
| **Retry Pattern**              | Tekrar Deneme Deseni – Geçici hatalarda işlemin yeniden denenmesi                                                      |
| **Timeout**                    | Zaman Aşımı – Servisten belirli süre içinde cevap alınamazsa işlemin iptal edilmesi                                    |
| **Load Balancing**             | Yük Dengeleme – İsteklerin birden fazla servise dengeli şekilde dağıtılması                                            |
| **Synchronous Communication**  | Senkron İletişim – Servisler arası doğrudan ve anlık yanıt bekleyen iletişim (REST, gRPC)                              |
| **Asynchronous Communication** | Asenkron İletişim – Mesaj kuyruğu veya event ile gecikmeli iletişim                                                    |
| **Message Broker**             | Mesaj Aracısı – Servisler arası mesajlaşmayı yöneten sistem (örneğin Kafka, RabbitMQ)                                  |
| **Event-Driven Architecture**  | Olay Tabanlı Mimari – Servislerin olaylara tepki vererek çalıştığı yapı                                                |
| **Saga Pattern**               | Saga Deseni – Dağıtık sistemlerde işlem tutarlılığı sağlamak için kullanılan iş akışı modeli                           |
| **Outbox Pattern**             | Outbox Deseni – Veritabanı ile mesajlaşma sisteminin senkron tutulduğu veri dayanıklılığı deseni                       |
| **Eventual Consistency**       | Zamanla Tutarlılık – Dağıtık sistemde anlık değil ama sonunda tüm verinin tutarlı hale gelmesi                         |
| **Distributed Tracing**        | Dağıtık İzleme – Bir işlemde yer alan tüm mikroservislerin zincirleme izlenmesi                                        |
| **Correlation ID**             | İlişkilendirme Kimliği – Farklı servislerdeki logları bir arada tutmak için kullanılan benzersiz kimlik                |
| **CI/CD**                      | Sürekli Entegrasyon / Sürekli Dağıtım – Kodun otomatik test edilip devreye alınması süreci                             |
| **Container**                  | Konteyner – Servislerin izole çalıştığı, hafif sanallaştırılmış ortam                                                  |
| **Container Orchestration**    | Konteyner Orkestrasyonu – Çok sayıda konteynerin yönetilmesi (Kubernetes gibi)                                         |
| **Blue-Green Deployment**      | Mavi-Yeşil Dağıtım – Yeni versiyonun canlıya risksiz geçişini sağlayan deployment stratejisi                           |
| **Canary Release**             | Kanarya Dağıtımı – Yeni versiyonun küçük bir kullanıcı grubuna gösterilerek test edilmesi                              |
| **Sidecar Pattern**            | Yan Servis Deseni – Ana servisle birlikte çalışan yardımcı servis (örneğin logging, proxy)                             |
| **Service Mesh**               | Servis Ağı – Servisler arası iletişimi, güvenliği ve gözlemlenebilirliği yöneten yapı (örneğin Istio)                  |
| **Zero Downtime Deployment**   | Kesintisiz Yayın – Sistemde hiç duraksama olmadan yeni sürüm geçişi                                                    |
| **Monolith**                   | Tek Yığın (Monolit) – Tüm bileşenlerin tek bir uygulama olarak geliştirildiği yapı                                     |
| **Decomposition**              | Ayrıştırma – Monolit uygulamayı mikroservislere bölme süreci                                                           |
| **Polyglot Persistence**       | Çoklu Veri Saklama – Her servisin ihtiyacına göre farklı veritabanı kullanabilmesi (SQL, NoSQL)                        |
| **Database per Service**       | Servis Başına Veritabanı – Her servisin kendi veritabanına sahip olması kuralı                                         |
| **Cross-Cutting Concerns**     | Katmanlar Arası Ortak Problemler – Logging, authentication, caching gibi tüm servisleri ilgilendiren konular           |
| **Domain Driven Design (DDD)** | Alan Odaklı Tasarım – Sistemin iş kuralları üzerinden modellenmesini sağlayan yaklaşım                                 |
| **Test Pyramid**               | Test Piramidi – En fazla unit test, daha az integration test, en az end-to-end test yapılması gerektiğini anlatan yapı |
| **Fault Tolerance**            | Hata Toleransı – Sistemin bazı bileşenleri hata verse bile genel işlevini sürdürebilmesi                               |
| **Backpressure**               | Geri Basınç – Aşırı yüklenmeyi önlemek için isteklerin yavaşlatılması veya düşürülmesi                                 |
