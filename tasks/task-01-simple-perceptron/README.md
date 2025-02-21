PERCEPTRON: 
a) Executar via terminal - Execute o script passando o argumento necessário:

python perceptron1.py --registration_number 12345

Substituindo "12345" por qualquer número que queira usar como semente para gerar os dados.

b) Fornecer um valor padrão no código Se quiser testar sem precisar passar argumentos manualmente, modifique a linha:

parser.add_argument('--registration_number', type=int, required=True, help="Student's registration number (used as seed)")

por

parser.add_argument('--registration_number', type=int, default=42, help="Student's registration number (used as seed)")