# mvn-archetype-quickstart
Maven Archetype Quickstart

# Install Apache Maven
Download : https://maven.apache.org/download.cgi

Setting Path di (Win10) System Properties - Enviroment Variable

Check maven di Command Prompt, untuk mengetahui apakah sudah terinstall atau belum
> mvn --version

# Untuk Create Project, ketik perintah di cmd : 
> mvn archetype:generate
> maven-archetype-quickstart

Nanti ada pilihan Remote, pilih yang berasal dari org.apache.maven.archetypes

GroupId : Biasa nya digunakan untuk nama Company
ArtifactId : Biasa nya untuk nama project nya

# Command Maven
clean : Menghapus Folder Kompilasi
compile : mengkompilasi source code 
test-compile : untuk kompilasi source code test
test : menjalankan unit test

Contoh :
> mvn compile
Jika bersamaan, ketik
> mvn clean,compile
