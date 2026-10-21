-- 1. Output
Escreva um código para mostrar mensagens na tela em C++
#include <iostream>
using namespace std;

int main() {
    cout << "Ola, mundo!" << endl;
    cout << "Estou aprendendo C++" << endl;
    return 0;
}


-- 2. Input
Escreva um código para receber informações do usuário em C++
#include <iostream>
#include <string>
using namespace std;

int main() {
    string nome;

    cout << "Digite seu nome: ";
    cin >> nome;

    cout << "Ola, " << nome << "!" << endl;
    return 0;
}


-- 3. Variáveis
Escreva um código para armazenar informações em variáveis C++
#include <iostream>
#include <string>
using namespace std;

int main() {
    int idade = 18;
    float altura = 1.75f;
    double saldo = 250.50;
    char letra = 'A';
    bool programador = true;
    string nome = "Caio";

    cout << nome << endl;
    cout << idade << endl;
    cout << altura << endl;
    cout << saldo << endl;
    cout << letra << endl;
    cout << programador << endl;

    return 0;
}


-- 4. Operadores Aritméticos
Escreva um código para realizar operações matemáticas em C++
#include <iostream>
using namespace std;

int main() {
    int a = 10;
    int b = 3;

    cout << a + b << endl;
    cout << a - b << endl;
    cout << a * b << endl;
    cout << a / b << endl;
    cout << a % b << endl;

    return 0;
}


-- 5. If e Else
Escreva um código para executar condições em C++
#include <iostream>
using namespace std;

int main() {
    int idade;

    cout << "Digite sua idade: ";
    cin >> idade;

    if (idade >= 18) {
        cout << "Maior de idade" << endl;
    } else {
        cout << "Menor de idade" << endl;
    }

    return 0;
}


-- 6. Else If
Escreva um código para verificar várias condições em C++
#include <iostream>
using namespace std;

int main() {
    int nota;
    cin >> nota;

    if (nota >= 9) {
        cout << "Excelente";
    } else if (nota >= 7) {
        cout << "Aprovado";
    } else if (nota >= 5) {
        cout << "Recuperacao";
    } else {
        cout << "Reprovado";
    }

    return 0;
}


-- 7. Switch
Escreva um código para escolher entre várias opções em C++
#include <iostream>
using namespace std;

int main() {
    int opcao;
    cin >> opcao;

    switch (opcao) {
        case 1:
            cout << "Jogar";
            break;
        case 2:
            cout << "Configuracoes";
            break;
        case 3:
            cout << "Sair";
            break;
        default:
            cout << "Opcao invalida";
    }

    return 0;
}


-- 8. While
Escreva um código para repetir comandos enquanto uma condição for verdadeira em C++
#include <iostream>
using namespace std;

int main() {
    int contador = 1;

    while (contador <= 5) {
        cout << contador << endl;
        contador++;
    }

    return 0;
}


-- 9. Do While
Escreva um código para executar comandos pelo menos uma vez em C++
#include <iostream>
using namespace std;

int main() {
    int numero;

    do {
        cout << "Digite um numero maior que zero: ";
        cin >> numero;
    } while (numero <= 0);

    cout << "Numero aceito!";
    return 0;
}


-- 10. For
Escreva um código para repetir comandos usando um contador em C++
#include <iostream>
using namespace std;

int main() {
    for (int i = 1; i <= 10; i++) {
        cout << i << endl;
    }

    return 0;
}


-- 11. Funções
Escreva um código para criar e chamar uma função em C++
#include <iostream>
using namespace std;

void saudacao() {
    cout << "Bem-vindo ao C++!" << endl;
}

int main() {
    saudacao();
    return 0;
}


-- 12. Funções com Parâmetros
Escreva um código para enviar informações para uma função em C++
#include <iostream>
using namespace std;

void apresentar(string nome) {
    cout << "Ola, " << nome << "!" << endl;
}

int main() {
    apresentar("Caio");
    apresentar("Lucas");
    return 0;
}


-- 13. Return
Escreva um código para retornar um resultado de uma função em C++
#include <iostream>
using namespace std;

int somar(int a, int b) {
    return a + b;
}

int main() {
    int resultado = somar(10, 5);
    cout << resultado << endl;
    return 0;
}


-- 14. Arrays
Escreva um código para armazenar vários valores em um array C++
#include <iostream>
using namespace std;

int main() {
    int numeros[5] = {10, 20, 30, 40, 50};

    cout << numeros[0] << endl;
    cout << numeros[1] << endl;
    cout << numeros[2] << endl;

    return 0;
}


-- 15. Vetores (Vector)
Escreva um código para usar um vetor que pode crescer em C++
#include <iostream>
#include <vector>
using namespace std;

int main() {
    vector<int> numeros = {10, 20, 30};

    numeros.push_back(40);
    numeros.push_back(50);

    for (int numero : numeros) {
        cout << numero << endl;
    }

    return 0;
}


-- 16. Strings
Escreva um código para manipular textos em C++
#include <iostream>
#include <string>
using namespace std;

int main() {
    string nome = "Programacao";

    cout << nome << endl;
    cout << nome.length() << endl;
    cout << nome[0] << endl;

    nome += " C++";
    cout << nome << endl;

    return 0;
}


-- 17. Booleanos
Escreva um código para trabalhar com valores verdadeiros e falsos em C++
#include <iostream>
using namespace std;

int main() {
    bool ativo = true;
    bool bloqueado = false;

    cout << boolalpha;
    cout << ativo << endl;
    cout << bloqueado << endl;

    return 0;
}


-- 18. Operadores Lógicos
Escreva um código para combinar condições em C++
#include <iostream>
using namespace std;

int main() {
    int idade = 20;
    bool temIngresso = true;

    if (idade >= 18 && temIngresso) {
        cout << "Entrada permitida";
    }

    return 0;
}


-- 19. Operadores de Comparação
Escreva um código para comparar valores em C++
#include <iostream>
using namespace std;

int main() {
    int a = 10;
    int b = 20;

    cout << (a == b) << endl;
    cout << (a != b) << endl;
    cout << (a < b) << endl;
    cout << (a > b) << endl;
    cout << (a <= b) << endl;
    cout << (a >= b) << endl;

    return 0;
}


-- 20. Constantes
Escreva um código para criar valores que não podem ser alterados em C++
#include <iostream>
using namespace std;

int main() {
    const double PI = 3.14159;
    const int ANO = 2026;

    cout << PI << endl;
    cout << ANO << endl;

    return 0;
}


-- 21. Enum
Escreva um código para definir um conjunto de opções nomeadas em C++
#include <iostream>
using namespace std;

enum class Estado {
    Menu,
    Jogando,
    Pausado
};

int main() {
    Estado estado = Estado::Jogando;

    if (estado == Estado::Jogando) {
        cout << "O jogo esta rodando";
    }

    return 0;
}


-- 22. Struct
Escreva um código para agrupar informações em uma estrutura C++
#include <iostream>
#include <string>
using namespace std;

struct Jogador {
    string nome;
    int nivel;
};

int main() {
    Jogador jogador = {"Caio", 10};

    cout << jogador.nome << endl;
    cout << jogador.nivel << endl;

    return 0;
}


-- 23. Classes e Objetos
Escreva um código para criar uma classe e um objeto em C++
#include <iostream>
#include <string>
using namespace std;

class Jogador {
public:
    string nome;
    int vida = 100;

    void mostrarVida() {
        cout << nome << ": " << vida << " HP" << endl;
    }
};

int main() {
    Jogador jogador;
    jogador.nome = "Caio";
    jogador.mostrarVida();

    return 0;
}


-- 24. Construtores
Escreva um código para inicializar objetos automaticamente em C++
#include <iostream>
#include <string>
using namespace std;

class Pessoa {
public:
    string nome;

    Pessoa(string nomeInicial) {
        nome = nomeInicial;
    }
};

int main() {
    Pessoa pessoa("Caio");
    cout << pessoa.nome << endl;

    return 0;
}


-- 25. Encapsulamento
Escreva um código para proteger dados de uma classe em C++
#include <iostream>
using namespace std;

class Conta {
private:
    double saldo = 0;

public:
    void depositar(double valor) {
        if (valor > 0) {
            saldo += valor;
        }
    }

    double consultarSaldo() {
        return saldo;
    }
};

int main() {
    Conta conta;
    conta.depositar(100);

    cout << conta.consultarSaldo() << endl;
    return 0;
}


-- 26. Herança
Escreva um código para criar uma classe derivada de outra em C++
#include <iostream>
using namespace std;

class Animal {
public:
    void comer() {
        cout << "O animal esta comendo" << endl;
    }
};

class Cachorro : public Animal {
public:
    void latir() {
        cout << "Au au!" << endl;
    }
};

int main() {
    Cachorro cachorro;
    cachorro.comer();
    cachorro.latir();

    return 0;
}


-- 27. Polimorfismo
Escreva um código para permitir comportamentos diferentes usando uma interface comum em C++
#include <iostream>
using namespace std;

class Animal {
public:
    virtual void emitirSom() {
        cout << "Som de animal" << endl;
    }

    virtual ~Animal() = default;
};

class Cachorro : public Animal {
public:
    void emitirSom() override {
        cout << "Au au!" << endl;
    }
};

int main() {
    Cachorro cachorro;
    Animal* animal = &cachorro;

    animal->emitirSom();
    return 0;
}


-- 28. Ponteiros
Escreva um código para armazenar o endereço de uma variável em C++
#include <iostream>
using namespace std;

int main() {
    int numero = 50;
    int* ponteiro = &numero;

    cout << numero << endl;
    cout << &numero << endl;
    cout << ponteiro << endl;
    cout << *ponteiro << endl;

    return 0;
}


-- 29. Referências
Escreva um código para criar um apelido para uma variável em C++
#include <iostream>
using namespace std;

int main() {
    int numero = 10;
    int& referencia = numero;

    referencia = 25;

    cout << numero << endl;

    return 0;
}


-- 30. Tratamento de Exceções
Escreva um código para tratar erros usando try, catch e throw em C++
#include <iostream>
#include <stdexcept>
using namespace std;

int dividir(int a, int b) {
    if (b == 0) {
        throw invalid_argument("Divisao por zero");
    }

    return a / b;
}

int main() {
    try {
        cout << dividir(10, 0);
    } catch (const exception& erro) {
        cout << "Erro: " << erro.what() << endl;
    }

    return 0;
}


-- 31. Arquivos
Escreva um código para gravar informações em um arquivo em C++
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ofstream arquivo("dados.txt");

    if (arquivo.is_open()) {
        arquivo << "Aprendendo C++" << endl;
        arquivo.close();
        cout << "Arquivo criado";
    }

    return 0;
}


-- 32. Ler Arquivos
Escreva um código para ler informações de um arquivo em C++
#include <iostream>
#include <fstream>
#include <string>
using namespace std;

int main() {
    ifstream arquivo("dados.txt");
    string linha;

    while (getline(arquivo, linha)) {
        cout << linha << endl;
    }

    return 0;
}


-- 33. Algoritmos com sort
Escreva um código para ordenar valores em C++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> numeros = {5, 2, 8, 1, 3};

    sort(numeros.begin(), numeros.end());

    for (int numero : numeros) {
        cout << numero << " ";
    }

    return 0;
}


-- 34. Busca em Vetores
Escreva um código para procurar um valor em um vetor C++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> numeros = {10, 20, 30, 40};

    auto resultado = find(numeros.begin(), numeros.end(), 30);

    if (resultado != numeros.end()) {
        cout << "Valor encontrado";
    } else {
        cout << "Valor nao encontrado";
    }

    return 0;
}


-- 35. Funções Lambda
Escreva um código para criar uma função anônima em C++
#include <iostream>
using namespace std;

int main() {
    auto somar = [](int a, int b) {
        return a + b;
    };

    cout << somar(5, 3) << endl;

    return 0;
}


-- 36. Auto
Escreva um código para deixar o compilador deduzir o tipo de uma variável em C++
#include <iostream>
using namespace std;

int main() {
    auto idade = 18;
    auto altura = 1.75;
    auto nome = "Caio";

    cout << idade << endl;
    cout << altura << endl;
    cout << nome << endl;

    return 0;
}


-- 37. Include
Escreva um código para incluir bibliotecas em C++
#include <iostream>
#include <string>
#include <vector>
#include <cmath>

int main() {
    std::cout << std::sqrt(25) << std::endl;
    return 0;
}


-- 38. Namespace
Escreva um código para utilizar um namespace em C++
#include <iostream>

namespace Mensagens {
    void mostrar() {
        std::cout << "Ola!" << std::endl;
    }
}

int main() {
    Mensagens::mostrar();
    return 0;
}


-- 39. Break e Continue
Escreva um código para controlar a execução de loops em C++
#include <iostream>
using namespace std;

int main() {
    for (int i = 1; i <= 10; i++) {
        if (i == 3) {
            continue;
        }

        if (i == 7) {
            break;
        }

        cout << i << endl;
    }

    return 0;
}


-- 40. Recursão
Escreva um código para uma função chamar a si mesma em C++
#include <iostream>
using namespace std;

int fatorial(int n) {
    if (n <= 1) {
        return 1;
    }

    return n * fatorial(n - 1);
}

int main() {
    cout << fatorial(5) << endl;
    return 0;
}


-- 41. Operador Ternário
Escreva um código para escolher entre dois resultados em C++
#include <iostream>
using namespace std;

int main() {
    int idade = 20;

    string resultado = (idade >= 18) ? "Maior" : "Menor";

    cout << resultado << endl;
    return 0;
}


-- 42. Modificadores de Acesso
Escreva um código para usar public, private e protected em C++
#include <iostream>
using namespace std;

class Exemplo {
public:
    int publico = 10;

private:
    int privado = 20;

protected:
    int protegido = 30;
};

int main() {
    Exemplo exemplo;
    cout << exemplo.publico << endl;

    return 0;
}


-- 43. Destrutores
Escreva um código para executar uma ação quando um objeto é destruído em C++
#include <iostream>
using namespace std;

class Exemplo {
public:
    ~Exemplo() {
        cout << "Objeto destruido" << endl;
    }
};

int main() {
    Exemplo objeto;
    return 0;
}


-- 44. Listas (List)
Escreva um código para usar uma lista duplamente encadeada em C++
#include <iostream>
#include <list>
using namespace std;

int main() {
    list<int> numeros = {10, 20, 30};

    numeros.push_front(5);
    numeros.push_back(40);

    for (int numero : numeros) {
        cout << numero << " ";
    }

    return 0;
}


-- 45. Map
Escreva um código para armazenar pares de chave e valor em C++
#include <iostream>
#include <map>
using namespace std;

int main() {
    map<string, int> pontuacao;

    pontuacao["Caio"] = 100;
    pontuacao["Lucas"] = 200;

    cout << pontuacao["Caio"] << endl;

    return 0;
}


-- 46. Set
Escreva um código para armazenar valores únicos em C++
#include <iostream>
#include <set>
using namespace std;

int main() {
    set<int> numeros = {1, 2, 2, 3, 3, 4};

    for (int numero : numeros) {
        cout << numero << " ";
    }

    return 0;
}


-- 47. Stack
Escreva um código para usar uma pilha de dados em C++
#include <iostream>
#include <stack>
using namespace std;

int main() {
    stack<int> pilha;

    pilha.push(10);
    pilha.push(20);
    pilha.push(30);

    cout << pilha.top() << endl;

    pilha.pop();

    cout << pilha.top() << endl;

    return 0;
}


-- 48. Queue
Escreva um código para usar uma fila de dados em C++
#include <iostream>
#include <queue>
using namespace std;

int main() {
    queue<int> fila;

    fila.push(10);
    fila.push(20);
    fila.push(30);

    cout << fila.front() << endl;

    fila.pop();

    cout << fila.front() << endl;

    return 0;
}


-- 49. Números Aleatórios
Escreva um código para gerar números aleatórios em C++
#include <iostream>
#include <random>
using namespace std;

int main() {
    random_device dispositivo;
    mt19937 gerador(dispositivo());
    uniform_int_distribution<int> distribuicao(1, 100);

    cout << distribuicao(gerador) << endl;

    return 0;
}


-- 50. Math
Escreva um código para realizar cálculos matemáticos usando cmath em C++
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    cout << sqrt(25) << endl;
    cout << pow(2, 3) << endl;
    cout << abs(-10) << endl;
    cout << ceil(4.2) << endl;
    cout << floor(4.8) << endl;

    return 0;
}


-- 51. Validação de Input
Escreva um código para verificar se a entrada do usuário é válida em C++
#include <iostream>
using namespace std;

int main() {
    int idade;

    cout << "Digite sua idade: ";

    if (!(cin >> idade)) {
        cout << "Entrada invalida";
        return 1;
    }

    if (idade < 0) {
        cout << "Idade invalida";
        return 1;
    }

    cout << "Idade: " << idade << endl;
    return 0;
}


-- 52. getline
Escreva um código para ler uma linha completa de texto em C++
#include <iostream>
#include <string>
using namespace std;

int main() {
    string nomeCompleto;

    cout << "Digite seu nome completo: ";
    getline(cin, nomeCompleto);

    cout << "Ola, " << nomeCompleto << endl;
    return 0;
}


-- 53. Conversão de Tipos
Escreva um código para converter um tipo de dado em outro em C++
#include <iostream>
using namespace std;

int main() {
    double valor = 9.75;
    int inteiro = static_cast<int>(valor);

    cout << inteiro << endl;

    return 0;
}


-- 54. Variáveis Globais e Locais
Escreva um código para demonstrar variáveis globais e locais em C++
#include <iostream>
using namespace std;

int global = 100;

int main() {
    int local = 50;

    cout << global << endl;
    cout << local << endl;

    return 0;
}


-- 55. Argumentos da Linha de Comando
Escreva um código para receber argumentos ao executar um programa C++
#include <iostream>
using namespace std;

int main(int argc, char* argv[]) {
    cout << "Quantidade de argumentos: " << argc << endl;

    for (int i = 0; i < argc; i++) {
        cout << argv[i] << endl;
    }

    return 0;
}


-- 56. Ponteiros Inteligentes
Escreva um código para gerenciar memória usando unique_ptr em C++
#include <iostream>
#include <memory>
using namespace std;

int main() {
    unique_ptr<int> numero = make_unique<int>(100);

    cout << *numero << endl;

    return 0;
}


-- 57. Passagem por Referência
Escreva um código para alterar uma variável dentro de uma função em C++
#include <iostream>
using namespace std;

void dobrar(int& numero) {
    numero *= 2;
}

int main() {
    int valor = 10;

    dobrar(valor);

    cout << valor << endl;
    return 0;
}


-- 58. Passagem por Valor
Escreva um código para enviar uma cópia de uma variável para uma função em C++
#include <iostream>
using namespace std;

void alterar(int numero) {
    numero = 100;
}

int main() {
    int valor = 10;

    alterar(valor);

    cout << valor << endl;
    return 0;
}


-- 59. Sobrecarga de Funções
Escreva um código para criar funções com o mesmo nome e parâmetros diferentes em C++
#include <iostream>
using namespace std;

int somar(int a, int b) {
    return a + b;
}

double somar(double a, double b) {
    return a + b;
}

int main() {
    cout << somar(2, 3) << endl;
    cout << somar(2.5, 3.5) << endl;

    return 0;
}


-- 60. Sobrecarga de Operadores
Escreva um código para personalizar o operador + em uma classe C++
#include <iostream>
using namespace std;

class Ponto {
public:
    int x;

    Ponto(int valor) : x(valor) {}

    Ponto operator+(const Ponto& outro) const {
        return Ponto(x + outro.x);
    }
};

int main() {
    Ponto a(10);
    Ponto b(20);
    Ponto c = a + b;

    cout << c.x << endl;
    return 0;
}


-- 61. Templates
Escreva um código para criar uma função que trabalha com vários tipos em C++
#include <iostream>
using namespace std;

template <typename T>
T maior(T a, T b) {
    return (a > b) ? a : b;
}

int main() {
    cout << maior(10, 20) << endl;
    cout << maior(2.5, 1.5) << endl;

    return 0;
}


-- 62. Iteradores
Escreva um código para percorrer elementos de um vetor usando iteradores em C++
#include <iostream>
#include <vector>
using namespace std;

int main() {
    vector<int> numeros = {10, 20, 30};

    for (auto it = numeros.begin(); it != numeros.end(); ++it) {
        cout << *it << endl;
    }

    return 0;
}


-- 63. Const com Referências
Escreva um código para passar dados sem permitir sua alteração em C++
#include <iostream>
#include <string>
using namespace std;

void mostrar(const string& texto) {
    cout << texto << endl;
}

int main() {
    string mensagem = "Ola";
    mostrar(mensagem);

    return 0;
}


-- 64. constexpr
Escreva um código para criar valores calculados durante a compilação em C++
#include <iostream>
using namespace std;

constexpr int quadrado(int n) {
    return n * n;
}

int main() {
    constexpr int resultado = quadrado(5);

    cout << resultado << endl;
    return 0;
}


-- 65. static
Escreva um código para manter o valor de uma variável entre chamadas de função em C++
#include <iostream>
using namespace std;

void contador() {
    static int numero = 0;
    numero++;

    cout << numero << endl;
}

int main() {
    contador();
    contador();
    contador();

    return 0;
}


-- 66. std::optional
Escreva um código para representar um valor que pode estar ausente em C++17
#include <iostream>
#include <optional>
using namespace std;

optional<int> buscar(bool encontrado) {
    if (encontrado) {
        return 42;
    }

    return nullopt;
}

int main() {
    auto resultado = buscar(true);

    if (resultado.has_value()) {
        cout << resultado.value() << endl;
    }

    return 0;
}


-- 67. std::filesystem
Escreva um código para verificar se um arquivo existe em C++17
#include <iostream>
#include <filesystem>
using namespace std;

int main() {
    filesystem::path arquivo = "dados.txt";

    if (filesystem::exists(arquivo)) {
        cout << "Arquivo encontrado";
    } else {
        cout << "Arquivo nao encontrado";
    }

    return 0;
}


-- 68. std::chrono
Escreva um código para medir o tempo de execução em C++
#include <iostream>
#include <chrono>
using namespace std;
using namespace chrono;

int main() {
    auto inicio = steady_clock::now();

    for (int i = 0; i < 1000000; i++) {
        // Operacao de exemplo
    }

    auto fim = steady_clock::now();
    auto duracao = duration_cast<milliseconds>(fim - inicio);

    cout << "Tempo: " << duracao.count() << " ms" << endl;

    return 0;
}


-- 69. std::pair
Escreva um código para armazenar dois valores juntos em C++
#include <iostream>
#include <utility>
#include <string>
using namespace std;

int main() {
    pair<string, int> jogador = {"Caio", 10};

    cout << jogador.first << endl;
    cout << jogador.second << endl;

    return 0;
}


-- 70. std::tuple
Escreva um código para armazenar vários valores de tipos diferentes em C++
#include <iostream>
#include <tuple>
#include <string>
using namespace std;

int main() {
    tuple<string, int, double> pessoa = {"Caio", 18, 1.75};

    cout << get<0>(pessoa) << endl;
    cout << get<1>(pessoa) << endl;
    cout << get<2>(pessoa) << endl;

    return 0;
}


-- 71. std::all_of
Escreva um código para verificar se todos os elementos atendem a uma condição em C++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> numeros = {2, 4, 6, 8};

    bool todosPares = all_of(
        numeros.begin(),
        numeros.end(),
        [](int n) { return n % 2 == 0; }
    );

    cout << boolalpha << todosPares << endl;
    return 0;
}


-- 72. std::count_if
Escreva um código para contar elementos que atendem a uma condição em C++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> numeros = {1, 2, 3, 4, 5, 6};

    int pares = count_if(
        numeros.begin(),
        numeros.end(),
        [](int n) { return n % 2 == 0; }
    );

    cout << pares << endl;
    return 0;
}


-- 73. std::accumulate
Escreva um código para somar os elementos de um vetor em C++
#include <iostream>
#include <vector>
#include <numeric>
using namespace std;

int main() {
    vector<int> numeros = {10, 20, 30};

    int soma = accumulate(numeros.begin(), numeros.end(), 0);

    cout << soma << endl;
    return 0;
}


-- 74. std::replace
Escreva um código para substituir valores dentro de um vetor em C++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> numeros = {1, 2, 2, 3, 2};

    replace(numeros.begin(), numeros.end(), 2, 9);

    for (int n : numeros) {
        cout << n << " ";
    }

    return 0;
}


-- 75. std::reverse
Escreva um código para inverter a ordem dos elementos de um vetor em C++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> numeros = {1, 2, 3, 4, 5};

    reverse(numeros.begin(), numeros.end());

    for (int n : numeros) {
        cout << n << " ";
    }

    return 0;
}


-- 76. std::unique_ptr
Escreva um código para criar um objeto com gerenciamento automático de memória em C++
#include <iostream>
#include <memory>
using namespace std;

class Jogador {
public:
    int vida = 100;
};

int main() {
    auto jogador = make_unique<Jogador>();

    cout << jogador->vida << endl;
    return 0;
}


-- 77. std::shared_ptr
Escreva um código para compartilhar a propriedade de um objeto em C++
#include <iostream>
#include <memory>
using namespace std;

int main() {
    auto primeiro = make_shared<int>(50);
    auto segundo = primeiro;

    cout << *primeiro << endl;
    cout << *segundo << endl;
    cout << primeiro.use_count() << endl;

    return 0;
}


-- 78. std::weak_ptr
Escreva um código para observar um objeto sem compartilhar sua propriedade em C++
#include <iostream>
#include <memory>
using namespace std;

int main() {
    auto compartilhado = make_shared<int>(100);
    weak_ptr<int> observador = compartilhado;

    if (auto ponteiro = observador.lock()) {
        cout << *ponteiro << endl;
    }

    return 0;
}


-- 79. Mutex
Escreva um código para proteger dados compartilhados entre threads em C++
#include <iostream>
#include <thread>
#include <mutex>
using namespace std;

mutex mtx;
int contador = 0;

void incrementar() {
    lock_guard<mutex> bloqueio(mtx);
    contador++;
}

int main() {
    thread t1(incrementar);
    thread t2(incrementar);

    t1.join();
    t2.join();

    cout << contador << endl;
    return 0;
}


-- 80. Threads
Escreva um código para executar tarefas em paralelo em C++
#include <iostream>
#include <thread>
using namespace std;

void tarefa() {
    cout << "Tarefa executada" << endl;
}

int main() {
    thread t(tarefa);
    t.join();

    return 0;
}


-- 81. std::array
Escreva um código para usar um array com tamanho fixo em C++
#include <iostream>
#include <array>
using namespace std;

int main() {
    array<int, 3> numeros = {10, 20, 30};

    for (int n : numeros) {
        cout << n << endl;
    }

    return 0;
}


-- 82. std::deque
Escreva um código para adicionar e remover valores nas duas extremidades de uma sequência em C++
#include <iostream>
#include <deque>
using namespace std;

int main() {
    deque<int> numeros = {10, 20};

    numeros.push_front(5);
    numeros.push_back(30);

    for (int n : numeros) {
        cout << n << " ";
    }

    return 0;
}


-- 83. std::priority_queue
Escreva um código para acessar primeiro o maior valor de uma fila de prioridade em C++
#include <iostream>
#include <queue>
using namespace std;

int main() {
    priority_queue<int> fila;

    fila.push(10);
    fila.push(50);
    fila.push(20);

    cout << fila.top() << endl;

    return 0;
}


-- 84. std::binary_search
Escreva um código para verificar se um valor existe em uma sequência ordenada em C++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> numeros = {1, 3, 5, 7, 9};

    bool existe = binary_search(
        numeros.begin(),
        numeros.end(),
        5
    );

    cout << boolalpha << existe << endl;
    return 0;
}


-- 85. std::clamp
Escreva um código para manter um valor dentro de um limite em C++17
#include <iostream>
#include <algorithm>
using namespace std;

int main() {
    int volume = 120;

    volume = clamp(volume, 0, 100);

    cout << volume << endl;
    return 0;
}


-- 86. std::variant
Escreva um código para armazenar um de vários tipos possíveis em C++17
#include <iostream>
#include <variant>
#include <string>
using namespace std;

int main() {
    variant<int, double, string> dado = 42;

    cout << get<int>(dado) << endl;

    dado = string("Ola");
    cout << get<string>(dado) << endl;

    return 0;
}


-- 87. std::visit
Escreva um código para executar uma ação de acordo com o tipo armazenado em variant em C++17
#include <iostream>
#include <variant>
#include <string>
using namespace std;

int main() {
    variant<int, string> dado = "Programacao";

    visit([](const auto& valor) {
        cout << valor << endl;
    }, dado);

    return 0;
}


-- 88. std::any
Escreva um código para armazenar diferentes tipos de dados em C++17
#include <iostream>
#include <any>
#include <string>
using namespace std;

int main() {
    any dado = 100;
    cout << any_cast<int>(dado) << endl;

    dado = string("C++");
    cout << any_cast<string>(dado) << endl;

    return 0;
}


-- 89. std::string_view
Escreva um código para visualizar uma parte de um texto sem copiá-lo em C++17
#include <iostream>
#include <string_view>
using namespace std;

int main() {
    string_view texto = "Aprendendo C++";

    cout << texto.substr(0, 10) << endl;

    return 0;
}


-- 90. std::span
Escreva um código para acessar uma sequência de elementos sem assumir sua propriedade em C++20
#include <iostream>
#include <span>
using namespace std;

int main() {
    int numeros[] = {10, 20, 30};
    span<int> valores(numeros);

    for (int n : valores) {
        cout << n << endl;
    }

    return 0;
}


-- 91. Conceito de RAII
Escreva um código para liberar um recurso automaticamente quando um objeto sai de escopo em C++
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    {
        ofstream arquivo("exemplo.txt");
        arquivo << "O arquivo sera fechado automaticamente.";
    }

    cout << "O escopo terminou" << endl;
    return 0;
}


-- 92. static_cast
Escreva um código para converter tipos de forma explícita em C++
#include <iostream>
using namespace std;

int main() {
    double numero = 15.8;
    int resultado = static_cast<int>(numero);

    cout << resultado << endl;
    return 0;
}


-- 93. dynamic_cast
Escreva um código para converter um ponteiro polimórfico para um tipo derivado em C++
#include <iostream>
using namespace std;

class Animal {
public:
    virtual ~Animal() = default;
};

class Cachorro : public Animal {
public:
    void latir() {
        cout << "Au au!" << endl;
    }
};

int main() {
    Animal* animal = new Cachorro();

    if (Cachorro* cachorro = dynamic_cast<Cachorro*>(animal)) {
        cachorro->latir();
    }

    delete animal;
    return 0;
}


-- 94. assert
Escreva um código para verificar uma condição durante o desenvolvimento em C++
#include <iostream>
#include <cassert>
using namespace std;

int main() {
    int idade = 18;

    assert(idade >= 0);

    cout << "Condicao valida" << endl;
    return 0;
}


-- 95. static_assert
Escreva um código para verificar uma condição durante a compilação em C++
#include <iostream>
using namespace std;

int main() {
    static_assert(sizeof(int) >= 2, "Tipo int muito pequeno");

    cout << "Compilacao concluida" << endl;
    return 0;
}


-- 96. std::tie
Escreva um código para atribuir valores de uma tupla a variáveis existentes em C++
#include <iostream>
#include <tuple>
using namespace std;

int main() {
    tuple<int, double> dados = {10, 2.5};

    int idade;
    double altura;

    tie(idade, altura) = dados;

    cout << idade << endl;
    cout << altura << endl;

    return 0;
}


-- 97. std::transform
Escreva um código para transformar cada elemento de um vetor em C++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> numeros = {1, 2, 3, 4};
    vector<int> quadrados(numeros.size());

    transform(
        numeros.begin(),
        numeros.end(),
        quadrados.begin(),
        [](int n) { return n * n; }
    );

    for (int n : quadrados) {
        cout << n << " ";
    }

    return 0;
}


-- 98. std::remove_if
Escreva um código para remover logicamente elementos que atendem a uma condição em C++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> numeros = {1, 2, 3, 4, 5, 6};

    numeros.erase(
        remove_if(
            numeros.begin(),
            numeros.end(),
            [](int n) { return n % 2 == 0; }
        ),
        numeros.end()
    );

    for (int n : numeros) {
        cout << n << " ";
    }

    return 0;
}


-- 99. std::lower_bound
Escreva um código para encontrar a primeira posição adequada para inserir um valor em uma sequência ordenada em C++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> numeros = {10, 20, 30, 40};

    auto posicao = lower_bound(
        numeros.begin(),
        numeros.end(),
        25
    );

    cout << *posicao << endl;
    return 0;
}


-- 100. Programa Completo
Escreva um programa que combine input, output, funções, condições e loops em C++
#include <iostream>
#include <string>
using namespace std;

bool aprovado(double nota) {
    return nota >= 7.0;
}

int main() {
    string nome;
    double nota;

    cout << "Digite seu nome: ";
    getline(cin, nome);

    cout << "Digite sua nota: ";
    cin >> nota;

    if (aprovado(nota)) {
        cout << nome << " foi aprovado!" << endl;
    } else {
        cout << nome << " precisa estudar mais." << endl;
    }

    cout << "Contagem: ";

    for (int i = 1; i <= 5; i++) {
        cout << i << " ";
    }

    cout << endl;
    return 0;
}