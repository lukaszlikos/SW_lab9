# SW - przekład wykorzystania Github Actions 

Bardzo prosta aplikacja: serwer http ze statyczną stroną www 
Plik "./github/workflows/gha_example.yaml" definiuje:
pipeline GitHub Actions 
- budowanie obrazu multiarch, 
- przesłanie na Dockerhub z nowym tagiem, 
- wykorzystanie cache
