## Minhas imagens docker 

- docker save -o minha_imagem.tar minha_imagem:tag
- split -b 50M <seu_arquivo_grande> parte_
- cat parte_* > <seu_arquivo_grande>
- docker load -i <nome_do_arquivo.tar>
