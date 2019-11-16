Expressão regular para inserir o static nas respectivas tags do html para funcionar no django


find
(src|href)="((img|js|css).*?)"
replace
$1="{% static '$2' %}"