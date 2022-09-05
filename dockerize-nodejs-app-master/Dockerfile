#node 10 versiyonunu DockerHubdan indiriyoruz.
FROM node:10

#çalışacağımız image'imizin yapısı burda olacak
#WORKDIR /desktop/node/app
WORKDIR /home/node/app

# rest-api içindeki dosyaları /home/node/app 'e aktaralım
COPY rest-api /home/node/app

# çalışabilmesi için projenin içine node-modules yüklememiz gerekiyor
# npm node ile birlikte geldiği için direkt kullanabildik, node dışında başka bir şey kullansaydık npm'i de yüklememiz gerekirdi
# RUN komutu Docker daha image halindeyken çalıştırılır, CMD ise container çalışırken çalıştırılır
RUN npm install 

CMD npm run start

EXPOSE 3000

