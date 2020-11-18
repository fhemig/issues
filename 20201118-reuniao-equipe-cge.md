# REUNIÃO DADOS-MG-FHEMIG 18/11/2020

## Tópicos:

1. Apresentação repositório fhemig/dados-abertos;

2. Dificuldades encontradas;

3. Restrições de espaço para utilização do github como repositório de dados (https://dvc.org/ e https://git-lfs.github.com/ como alternativas) mas que não é problema para FHEMIG neste momento; e

4. Participar do evento que ocorrerá dia 01/12.

## Tarefas:

- [x] Incluir nos issues maneira de sincronizar repositórios no goodtables.io

- [ ] Exportar arquivo .csv com utilizando ";" como separador;

- [ ] Exportar arquivo .csv UTF-8 byte order markder (DBeaver) "Insert BOM" (https://en.wikipedia.org/wiki/Byte_order_mark);

- [ ] Exportar arquivo .csv com campo data formatado corretamente (https://specs.frictionlessdata.io/table-schema/#types-and-formats);

- [ ] Mudar estrutura de organização das pastas para que cada métrica seja um repositório dentro da organização fhemig. Substituir dados-abertos por paciente_dia, por exemplo;

- [ ] Modificar estrutura dapackage.json para referenciar todos os arquivos que serão validados, não apenas um (https://github.com/dados-mg/issues/issues/12);

- [ ] Criar repositório para armazenar glossário fhemig. Este glossário deverá ser referenciado (via link) em cada repositório que contenha dados disponibilizados;

- [ ] Incluir README.md dentro do repositório paciente_dia explicando o que é a métrica (Referenciando local correto dentro do repositório do glossário);

- [ ] Melhorar arquivo datapackage.json, com detalhamento maior dos campos e suas restrições;


