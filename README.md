# DOCKER_101

dockerize-nodejs-app-master : KablosuzKedi kanalından alınmıştır Link : https://www.youtube.com/watch?v=4G7zjbAKUb4

Dockerfile oluşturulduktan sonra:
`docker build --tag node-rest-api .`


Çalıştırmak için:
`docker run -p 3000:3000 node-rest-api`
İlk 3000 bilgisayarımızdan ikinci 3000'e gitmek için kullandığımız adres. İlla 3000 olmak zorunda değil. 1234 yazarsak da localhost:1234/users şeklinde Rest API'mize ulaşabiliriz. Fakat komut satırındaki ikinci 3000 kod içerisinde kullandığımız 3000'dir. Eğer onu değiştirirsek çalışmaz.


nodeapp-test-master ==> https://www.youtube.com/watch?v=CfPRbdT-wXo&list=LL&index=4
