## Malware com python

- Ele criptografa com o ```madara.py```
- E descriptografa com o ```guy_sensei.py```

## Instalar

Para instalar você vai precisar digitar os comandos:

```
apt update
apt upgrade
sudo apt install git
git clone https://github.com/elliot5x/crypt.git
cd crypt
```
## Como usar

Eu deixei dois ".txt" para vc textar se está funcionando bem, mas claro que vc pode excluir e criar outros ".txt" da sua escolha.

Para usar você terá que primeiro entrar na pasta obviamente, usando:
```
cd crypt
```
depois é só ler os dois arquivos .txt e ver se estão normais, rodando:
```
cat primeirotexto.txt
ou 
cat segundotexto.txt
```

Se aparecer o texto embaixo como "primeiro texto" ou "segundo texto" significa que está indo bem.

Continuando...
Agora é só criptografar o texto dos arquivos rodando o programa usando:
```
python3 madara.py
```
E pronto já está criptografado. (vale lembrar que o ```madara.py``` é o responsavél por criptografar enquanto que o ```guy_sensei.py``` descriptografa)

Se você for tentar ler os arquivos agr usando aquele comando:
```
cat primeirotexto.txt
ou
cat segundotexto.txt
```
Eles irão estar criptografados.

Agora para descriptografar é muito simples, basta rodar o ```guy_sensei``` e pronto, estará tudo normal denovo
rode ele usando:
```
python3 guy_sensei.py
```

## Thanks

- Claro, isso é super simples e talvez limitado, mas você pode tornar o codigo mais robusto e melhor, basta mandar suas dicas ai.