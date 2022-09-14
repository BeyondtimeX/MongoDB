![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

* show databases;

* use beyondtime;

* db.createCollection ('Minha coleção');

* db.createCollection ('Minha coleção 2');

* show collections;

![image](https://user-images.githubusercontent.com/88558377/190068951-07c170e1-5216-4946-8630-3092c36c772c.png)

 * db.createCollection ('Minha coleção 3');
 
 * db.createCollection ('Postagens');
 
* db.Postagens.insertOne({nome:'Bruno Almeida',conteudo:'Minha comunicação de exemplo'})

 * db.Postagens.insertOne({nome:'Bruno de Souza',conteudo:'Minhas consideraçõesde exemplo'})
  
  ![image](https://user-images.githubusercontent.com/88558377/190072005-6a7ba0cb-f1a0-4959-9b86-54f103c74f8f.png)
  

  * db.Postagens.find({})
  
  
  ![image](https://user-images.githubusercontent.com/88558377/190072363-05a3fae1-ef42-46e4-bf08-d017edb68e31.png)
  
  * db.Postagens.updateOne({nome:"Bruno Almeida"},{$set:{nome:"Isaias Oliveira"}
  
  ![image](https://user-images.githubusercontent.com/88558377/190074098-3d42a0a8-d5d5-4c7d-96f3-e9c3db49cf20.png)
  

 * db.Postagens.find({})
  
  
  ![image](https://user-images.githubusercontent.com/88558377/190074168-010eeb48-84b3-4b80-864d-408df395024e.png)

  
  * db.Postagens.insertOne({Comentarios:[2,3,4,6,8]})
  
  * db.Postagens.find({"Comentarios":{$ne:null}})
  
 * db.Postagens.find({"Comentarios":[2,3,4,6,8]})
  
  
  ![image](https://user-images.githubusercontent.com/88558377/190077029-0048f321-76a7-4715-b0e0-ce69b2297f87.png)

 * db.Postagens.deleteOne({nome:"Isaias Oliveira"})
  
  ![image](https://user-images.githubusercontent.com/88558377/190078976-1df1e729-9006-4e4f-87a3-da81e3dc8ab4.png)
  
 * db.Postagens.insertMany([{noticia:"minha noticia",autores:['Bruno','Isabela'],comentarios:[{nome:'Joana',comentario:'Meu comentário de teste'},{nome:'Jose',comentario:'Esse é o comentário do Jose'}]}]);
  
  ![image](https://user-images.githubusercontent.com/88558377/190087589-69be7a05-461f-417f-a933-8ea96bcd5946.png)


  
  
  
  
