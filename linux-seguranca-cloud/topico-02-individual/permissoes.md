# Permissões aplicadas

## Ambiente utilizado

VM local (Ubuntu em VirtualBox)

## Utilizador e grupos

Comandos utilizados:

whoami
id
groups

Estes comandos permitiram identificar o utilizador atual e os grupos associados.

## Ficheiros criados

* publico.txt
* restrito.txt
* script.sh

## Permissões aplicadas

| Ficheiro     | Permissão | Justificação                                                   |
| ------------ | --------- | -------------------------------------------------------------- |
| publico.txt  | 644       | Pode ser lido por todos, mas apenas alterado pelo proprietário |
| restrito.txt | 640       | Apenas proprietário e grupo podem consultar                    |
| script.sh    | u+x       | Permite execução apenas ao proprietário                        |

## Relação com o princípio do menor privilégio

As permissões atribuídas garantem que cada ficheiro possui apenas os acessos necessários à sua finalidade. Desta forma reduz-se o risco de alterações indevidas, acesso não autorizado e exposição de informação sensível.
