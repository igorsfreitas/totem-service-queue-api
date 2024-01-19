# totem-service-queue-api
Sistema de Gerenciamento de Filas de Atendimento

## Tecnologias Usadas:
- GO Lang
- NodeJS
- Javascript
- ReactJS

### Descritivo Básico:
  Aplicação foi desenvolvida inicialmente pensando em agregar serviço para diversos tipos de segmentos.
  Foi então efetuado o levantamento da demanda real para esse desenvolvimento:
<br>  -> Ser possível a inclusão de várias filas de atendimentos (normal, idosos, idosos com +80 anos, etc...)
<br>  -> Especificar quais clients iriam chamar determinadas filas, não sendo possível chamar outras filas além das determinadas.
<br>  -> Os atendentes podem chamar de qualquer computador desde que os mesmos tenham permissão para as filas que aquele computador tenha permissão. Eles também tem uma quantidade limite para re-chamar a senha x vezes, conforme configurado nas configurações gerais no Painel Administrativo.
<br>  -> As filas de atendimentos também tem configurações específicas para funcionar dentro de um terminado horário, por exemplo, a fila de Transporte (Normal, Preferencial) em Caruaru, podem ser impressas das 07:30 às 16:59, mesmo o restante dos atendimentos funcionar até as 18:00.
<br>  -> As senhas das filas são impressas em uma impressora térmica com suporte a ESC/POS, atualmente usada impressora EPSON TM-T20 com Ethernet.
<br>  -> O sistema contempla também uma API que funciona para integração com outro sistema voltado a gestão farmaceutica, sendo que os médicos ou o pessoal que faz a triagem, podem chamar os pacientes no painel de chamada pelo nome. Sendo que essa API só fica disponível para uso interno na mesma rede aonde está funcionando. Ex.: 192.168.33.0/24


### Captura de Telas
![Ainda em construção](http://google.com.br Construção")

## Instalação

### **1. Baixando o projeto:**

```
>git clone https://github.com/igorsfreitas/totem-service-queue-api.git
```

### **2. Instalando as dependências:**

Esse projeto foi feito usando **NodeJS**, baixe no site e instale de acordo com o seu sistema operacional.

```
>cd totem-service-queue-api
>yarn
```

### **3. Iniciando o Painel**

```
>yarn run dev
```

## Como Funciona

Assim que aparecer:

```
>Server Running: http://localhost:3000
```

### **1. Usando o Chrome ou Mozilla digite a url http://localhost:3000**

### EM BREVE MAIORES INFORMAÇÕES

-----------------------------------------

## Referências

https://github.com/sialka/ccb-panel
https://github.com/igormenin/phpsgf
https://github.com/novosga/doc/blob/master/using.rst


