<style>
img[src*='#center'] { 
    display: block;
    margin: auto;
}
</style>
# Simple Blog Post

Repository ini adalah sebuah proyek yang bertujuan untuk mendemonstrasikan implementasi microservices pada suatu sistem, meskipun masih menggunakan database bersama (shared database) ~~karena ini gratis~~. Dalam repository ini, Anda dapat menemukan berbagai sumber daya seperti kode contoh, dokumentasi, dan tutorial yang berguna untuk mempelajari tentang konsep-konsep dasar dan teknik-teknik yang digunakan dalam pengembangan microservices. Proyek ini juga dapat membantu Anda memahami bagaimana memecah aplikasi besar menjadi layanan-layanan kecil yang lebih mudah untuk dikelola dan diubah. Meskipun menggunakan shared database, repository ini memberikan gambaran umum tentang bagaimana konsep-konsep dan teknik-teknik yang digunakan dalam pengembangan microservices dapat diterapkan pada sistem yang lebih besar


# Architecture Design
_This architecture design is subject to change._   
  
![architercture](./assets/img/architecture.png#center)   

1.  Kenapa menggunakan PostgreSQL?   
    Karena ini gratis hehehe    
2.  Kenapa tidak menggunakan mongodb?   
    Karena saat ini di Indonesia lebih banyak menggunakan SQL sebagai database utama sehingga memudahkan proses belajar. Mungkin kedepannya dapat menggunakan mongodb untuk service baru    
3.  Kenapa shared database? microservice kan 1 service 1 database?    
    _*karena ini proyek gratis!!*_    
4.  Kenapa tidak menggunakan API GATEWAY, redis dll?      
    *IDEM*    
5.  Bagaimana _database desgin_ nya?   
    Hubungi [ini](https://t.me/fajar_afi)


# Bagaimana cara kontribusi?
1. Fork repository ini   
2. Buat branch baru lalu push ke private repo Anda. Untuk *fitur* gunakan penamaan `feature/<nama-feature>`. Untuk *bug fixing* gunakan `fix/<info-fixing>`. Untuk *improvement* `improv/<nama-improvment>`    
3. Push ke private repo kalian    
4. Buat pull request ke repo ini dengan nama branch kalian    
5. Proses code review, jika setuju akan di merge ke master    
