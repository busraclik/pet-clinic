🐾 Pet Clinic Application
Bu proje, Spring Boot kullanılarak geliştirilmiş basit bir Veteriner Yönetim Sistemi’dir.
Uygulama, hayvan sahipleri (Owner), hayvanlar (Pet), veterinerler (Vet) ve ziyaret kayıtlarını (Visit) yönetmek için tasarlanmıştır.
Proje iki ana modülden oluşur:
pet-clinic-data: Uygulamanın veri katmanını içerir (Entity, Repository, Service).
pet-clinic-web: Uygulamanın web katmanını içerir (Controller, View).
🔧 Kullanılan Teknolojiler
Java 17
Spring Boot (Web, Data JPA, Thymeleaf, Validation, Actuator)
H2 Database & MySQL
Lombok
WebJars (Bootstrap, jQuery)
JUnit 5 & Mockito
📚 Özellikler
Sahip (Owner) oluşturma, güncelleme ve listeleme
Hayvan (Pet) ekleme ve ilişkili sahibine bağlama
Veteriner (Vet) bilgilerini yönetme
Ziyaret (Visit) kayıtlarını oluşturma ve görüntüleme
🚀 Çalıştırma
Projeyi klonladıktan sonra aşağıdaki komutlarla çalıştırabilirsin:
mvn clean install
mvn spring-boot:run -pl pet-clinic-web
Uygulama varsayılan olarak http://localhost:8080 adresinde çalışır.
