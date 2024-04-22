### Reflection Tutorial 8
#### Nama: Naufal Ichsan
#### NPM: 2206082013
#### Kelas: A  

1. **How many data your publlsher program will send to the message broker in one run?**      
Program publisher akan mengirimkan lima data ke message brocker dalam satu kali eksekusi. Hal ini karena ada lima panggilan metode publish_event, masing-masing mengirimkan sebuah UserCreatedEventMessage ke message brocker.  


2. **The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?**      
URL ```amqp://guest:guest@localhost:5672``` memiliki kesamaan dengan subscriber program. Ini menandakan baik subscriber maupun publisher terhubung ke server AMQP (Advanced Message Queuing Protocol) yang sama menggunakan kredensial yang sama (nama pengguna: "guest", sandi: "guest"), dan server berjalan pada localhost dengan port 5672.    


#### foto rabbitmq
![alt text](assets/images/rabbitmq.png)
#### foto terminal subscriber
![alt text](assets/images/terminal-subscriber.png)
#### foto terminal publisher
![alt text](assets/images/terminal-publisher.png)
