Atividade de padrão de projeto 

 padrões q eu estou ultilizando nesse projeto são:
 - Padão criacional o Factory Method
 - Padão estrutual o Adapter tambem conhecido como Wrapper
 - Padão comportamental o Template Method

 Cada um dos padroes estao comentado em como eu ultilizei na funcionalidade que implementei e tbm ultilizei para me basear nos padroes o site refactoring guri e o arquivo que foi implementado os padroes eh no "models.py"

 referencias:
 https://refactoring.guru/pt-br/design-patterns/factory-method
 https://refactoring.guru/pt-br/design-patterns/adapter
 https://refactoring.guru/pt-br/design-patterns/template-method

Abaixo os comando para rodar o sistema 

Usando a tecnologia Django

Passo a passo para que funcione sem problemas na maquina
Instale as seguintes informaçoes

Antes de tudo verifique se o python esta instaldo

no CMD digite o comando
python --vesion

crie um ambiente virtual na sua maquina
evita conflito de versão

No CMD rode

python -m venv venv

depois ative o ambiente virtual

Windows
venv\Scripit\activate

MAC/LINUX

source venv/bin/activate

instale o django

pip install django

para confirmar

django-admin --version

biblioteca que vai precisar para rodar o projeto

pip install django-allauth

pip install django-cors-headers