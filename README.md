# Inteligência Artificial

Repositório destinado às atividades desenvolvidas na disciplina de Inteligência Artificial.

## Conteúdos

- Exercícios de Python
- Notebooks desenvolvidos durante a disciplina
{
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/heloisafrancops-collab/Inteligencia-Artificial1/blob/main/Exercicios_Python.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "UToSTxSkONzx",
        "outputId": "aece94fd-8d14-466c-cf86-e26016a3f88e"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Hello, World!\n"
          ]
        }
      ],
      "source": [
        "# =====================================================================\n",
        "# Exercício 1 - Hello, World!\n",
        "#\n",
        "# Explicação:\n",
        "# Esse primeiro exercício serve para mostrar como\n",
        "# funciona o comando print() em Python. Com ele, conseguimos exibir\n",
        "# uma mensagem na tela.\n",
        "# =====================================================================\n",
        "\n",
        "print(\"Hello, World!\")"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "O207EkOIPCz8",
        "outputId": "4ecb6338-2f3a-4fc4-afdf-d728bcf0eaa8"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite o primeiro número: 1\n",
            "Digite o segundo número: 5\n",
            "A soma é: 6\n"
          ]
        }
      ],
      "source": [
        "# Exercício 2 - Soma de Dois Números\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber os números digitados pelo usuário e o int() para converter esses valores para números inteiros. Depois usei o operador + para fazer a soma e o print() para mostrar o resultado na tela.\n",
        "numero1 = int(input(\"Digite o primeiro número: \"))\n",
        "numero2 = int(input(\"Digite o segundo número: \"))\n",
        "\n",
        "soma = numero1 + numero2\n",
        "\n",
        "print(\"A soma é:\", soma)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "6iUrfADFPCiw",
        "outputId": "01c54275-8630-442d-a8b4-f798e5897433"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite o raio do círculo: 20.5\n",
            "A área do círculo é: 1319.585\n"
          ]
        }
      ],
      "source": [
        "# Exercício 3 - Cálculo da Área do Círculo\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber o valor do raio, o float() para permitir números com casas decimais e utilizei a fórmula da área do círculo para fazer o cálculo. Depois usei o print() para mostrar o resultado.\n",
        "\n",
        "raio = float(input(\"Digite o raio do círculo: \"))\n",
        "\n",
        "pi = 3.14\n",
        "\n",
        "area = pi * raio ** 2\n",
        "\n",
        "print(\"A área do círculo é:\", area)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "AlA00pXQPCMr",
        "outputId": "9ac137a4-fbfc-4340-c620-d86bc2f96df3"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite a temperatura em Celsius: 10\n",
            "50.0\n"
          ]
        }
      ],
      "source": [
        "# Exercício 4 - Conversão de Temperatura\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber a temperatura em Celsius e apliquei a fórmula dada no exercício para converter o valor para Fahrenheit. Depois utilizei o print() para mostrar o resultado.\n",
        "\n",
        "celsius = float(input(\"Digite a temperatura em Celsius: \"))\n",
        "\n",
        "fahrenheit = (celsius * 9/5) + 32\n",
        "\n",
        "print(fahrenheit)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "O2R1kWg0O9_c",
        "outputId": "001ccd3a-34c7-482e-a2ec-61b144f5d015"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite um número: 5\n",
            "5 x 1 = 5\n",
            "5 x 2 = 10\n",
            "5 x 3 = 15\n",
            "5 x 4 = 20\n",
            "5 x 5 = 25\n",
            "5 x 6 = 30\n",
            "5 x 7 = 35\n",
            "5 x 8 = 40\n",
            "5 x 9 = 45\n",
            "5 x 10 = 50\n"
          ]
        }
      ],
      "source": [
        "# Exercício 5 - Tabuada\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber um número e o for para repetir a tabuada de 1 até 10. Depois usei o print() para mostrar os resultados.\n",
        "\n",
        "numero = int(input(\"Digite um número: \"))\n",
        "\n",
        "for i in range(1, 11):\n",
        "    print(numero, \"x\", i, \"=\", numero * i)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "z_g0xt29O_Wi",
        "outputId": "66f4ace5-6219-4e43-da06-79c190b8d685"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "2\n",
            "4\n",
            "6\n",
            "8\n",
            "10\n",
            "12\n",
            "14\n",
            "16\n",
            "18\n",
            "20\n"
          ]
        }
      ],
      "source": [
        "# Exercício 6 - Números Pares\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o for para percorrer os números de 1 a 20 e o if para verificar quais deles são pares. Depois usei o print() para mostrar os números.\n",
        "\n",
        "for numero in range(1, 21):\n",
        "    if numero % 2 == 0:\n",
        "        print(numero)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "ziu8xKibz8Xh",
        "outputId": "01c5a824-d9c4-4903-e8c6-fb9999c1c4e1"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite um número: 2\n",
            "O número é par.\n"
          ]
        }
      ],
      "source": [
        "# Exercício 7 - Número Ímpar ou Par\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber um número e o if para verificar se ele é par ou ímpar. Depois utilizei o print() para mostrar o resultado.\n",
        "\n",
        "numero = int(input(\"Digite um número: \"))\n",
        "\n",
        "if numero % 2 == 0:\n",
        "    print(\"O número é par.\")\n",
        "else:\n",
        "    print(\"O número é ímpar.\")"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "H2Xro_w4z8p3",
        "outputId": "fd6f8903-ed13-4405-80d5-3d8e889da4f9"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite uma palavra: ana\n",
            "É um palíndromo.\n"
          ]
        }
      ],
      "source": [
        "# Exercício 8 - Verificação de Palíndromo\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber uma palavra e comparei ela com a própria palavra invertida. Para inverter a palavra utilizei [::-1], onde os dois pontos (:) indicam que será percorrida toda a palavra e o -1 faz a leitura de trás para frente. Se a palavra original for igual à invertida, significa que ela é um palíndromo.\n",
        "\n",
        "palavra = input(\"Digite uma palavra: \")\n",
        "\n",
        "if palavra == palavra[::-1]:\n",
        "    print(\"É um palíndromo.\")\n",
        "else:\n",
        "    print(\"Não é um palíndromo.\")"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "5vEvzIZDz8xa",
        "outputId": "a4885e18-0489-4f90-f8af-fcd15dcf7b31"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite um número: 10\n",
            "3628800\n"
          ]
        }
      ],
      "source": [
        "# Exercício 9 - Fatorial de um Número\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber um número digitado pelo usuário. Criei a variável fatorial com o valor 1, pois ela será responsável por armazenar o resultado das multiplicações. Depois utilizei o for com o range() para percorrer todos os números de 1 até o número informado. O \"numero + 1\" foi utilizado porque o range() não considera o último valor, então foi necessário adicionar 1 para que o número digitado também participasse do cálculo. A cada repetição, o valor de fatorial é multiplicado pelo valor de i. No final, utilizei o print() para mostrar o resultado.\n",
        "\n",
        "numero = int(input(\"Digite um número: \"))\n",
        "\n",
        "fatorial = 1\n",
        "\n",
        "for i in range(1, numero + 1):\n",
        "    fatorial = fatorial * i\n",
        "\n",
        "print(fatorial)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Iljoz3VJz80c",
        "outputId": "60c52731-7f45-4314-9196-efdc9ed3ba0e"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite a quantidade de números da sequência: 5\n",
            "0\n",
            "1\n",
            "0 + 1 = 1\n",
            "1 + 1 = 2\n",
            "1 + 2 = 3\n"
          ]
        }
      ],
      "source": [
        "# Exercício 10 - Sequência de Fibonacci\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber a quantidade de números\n",
        "# da sequência que serão exibidos. Criei duas variáveis para armazenar os dois\n",
        "# primeiros números da sequência (0 e 1). Depois utilizei o for para repetir\n",
        "# o cálculo dos próximos números. A cada repetição, o próximo valor é encontrado\n",
        "# somando os dois números anteriores, mostrando também a operação realizada.\n",
        "\n",
        "quantidade = int(input(\"Digite a quantidade de números da sequência: \"))\n",
        "\n",
        "numero1 = 0\n",
        "numero2 = 1\n",
        "\n",
        "print(numero1)\n",
        "print(numero2)\n",
        "\n",
        "for i in range(2, quantidade):\n",
        "    proximo = numero1 + numero2\n",
        "\n",
        "    print(numero1, \"+\", numero2, \"=\", proximo)\n",
        "\n",
        "    numero1 = numero2\n",
        "    numero2 = proximo"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "JP3tPrQvz83w",
        "outputId": "44859ad9-ad9c-421e-bb04-dbc2171a02be"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Maior número: 20\n",
            "Menor número: 3\n"
          ]
        }
      ],
      "source": [
        "# Exercício 11 - Lista de Números\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei uma lista com alguns números e utilizei a função max() para encontrar o maior número da lista e a função min() para encontrar o menor. Depois utilizei o print() para mostrar os dois resultados.\n",
        "\n",
        "lista = [5, 12, 8, 20, 3, 15]\n",
        "\n",
        "print(\"Maior número:\", max(lista))\n",
        "print(\"Menor número:\", min(lista))"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "53Z3rvcxz86N",
        "outputId": "55979f74-1ffb-441b-85fb-101b08be2b7f"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite uma palavra ou frase: amor\n",
            "a : 1\n",
            "m : 1\n",
            "o : 1\n",
            "r : 1\n"
          ]
        }
      ],
      "source": [
        "# Exercício 12 - Contagem de Caracteres\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber uma palavra ou frase. Depois utilizei o for para percorrer cada caractere digitado. O if verifica se o caractere já existe no dicionário. Se existir, ele adiciona mais 1 à quantidade. Caso contrário, ele cria esse caractere no dicionário com o valor 1. No final utilizei outro for para mostrar quantas vezes cada caractere apareceu.\n",
        "\n",
        "texto = input(\"Digite uma palavra ou frase: \")\n",
        "\n",
        "contador = {}\n",
        "\n",
        "for letra in texto:\n",
        "    if letra in contador:\n",
        "        contador[letra] = contador[letra] + 1\n",
        "    else:\n",
        "        contador[letra] = 1\n",
        "\n",
        "for letra in contador:\n",
        "    print(letra, \":\", contador[letra])"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Qvv6A4z1z88v",
        "outputId": "5e6c43af-2619-4abe-b303-5c47dea68573"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "[1, 3, 6, 8, 10, 15]\n"
          ]
        }
      ],
      "source": [
        "# Exercício 13 - Ordenação de Lista\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei uma lista com alguns números e utilizei dois laços for para comparar os valores da lista. Quando um número era maior que o outro, troquei a posição deles. No final utilizei o print() para mostrar a lista em ordem crescente.\n",
        "\n",
        "lista = [8, 3, 15, 1, 10, 6]\n",
        "\n",
        "for i in range(len(lista)):\n",
        "    for j in range(i + 1, len(lista)):\n",
        "        if lista[i] > lista[j]:\n",
        "            aux = lista[i]\n",
        "            lista[i] = lista[j]\n",
        "            lista[j] = aux\n",
        "\n",
        "print(lista)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "LqqeCvlkz8-3",
        "outputId": "1b4432cd-622b-4d5f-8ead-73f5402354c3"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "A soma dos elementos da lista é: 75\n"
          ]
        }
      ],
      "source": [
        "# Exercício 14 - Soma dos Elementos de uma Lista\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei uma lista com alguns números e uma variável para armazenar a soma. Depois utilizei o for para percorrer todos os elementos da lista. A cada repetição, o valor do número é adicionado à variável soma. No final utilizei o print() para mostrar o resultado.\n",
        "\n",
        "lista = [5, 10, 15, 20, 25]\n",
        "\n",
        "soma = 0\n",
        "\n",
        "for numero in lista:\n",
        "    soma = soma + numero\n",
        "\n",
        "print(\"A soma dos elementos da lista é:\", soma)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "v3KSYXfCz9P6",
        "outputId": "27449d73-9b17-47d9-d6e5-ed83ef50d511"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "A média da lista é: 10.0\n"
          ]
        }
      ],
      "source": [
        "# Exercício 15 - Média de uma Lista\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei uma lista com alguns números e duas variáveis, uma para armazenar a soma dos elementos e outra para contar a quantidade de números da lista. Depois utilizei o for para percorrer todos os elementos, somando os valores e aumentando o contador. No final dividi a soma pela quantidade de elementos e utilizei o print() para mostrar a média.\n",
        "\n",
        "lista = [5, 10, 15]\n",
        "\n",
        "soma = 0\n",
        "quantidade = 0\n",
        "\n",
        "for numero in lista:\n",
        "    soma = soma + numero\n",
        "    quantidade = quantidade + 1\n",
        "\n",
        "media = soma / quantidade\n",
        "\n",
        "print(\"A média da lista é:\", media)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "UpYebAJTz9SF",
        "outputId": "641b721f-bfc8-4517-b4b6-c8f000649d58"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite uma palavra ou frase: amor\n",
            "String invertida: roma\n"
          ]
        }
      ],
      "source": [
        "# Exercício 16 - Manipulação de Strings\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber uma palavra ou frase. Depois utilizei [::-1] para inverter a string. Os dois pontos (:) indicam que será utilizada toda a string e o -1 faz a leitura de trás para frente. No final utilizei o print() para mostrar a string invertida.\n",
        "\n",
        "texto = input(\"Digite uma palavra ou frase: \")\n",
        "\n",
        "invertida = texto[::-1]\n",
        "\n",
        "print(\"String invertida:\", invertida)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "sdXNUCWRz9VC",
        "outputId": "ad2115a7-6a2f-4534-8156-43a30b88e2e2"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite uma frase: eu gosto de python e gosto de programar\n",
            "eu : 1\n",
            "gosto : 2\n",
            "de : 2\n",
            "python : 1\n",
            "e : 1\n",
            "programar : 1\n"
          ]
        }
      ],
      "source": [
        "# Exercício 17 - Dicionário de Contagem de Palavras\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber uma frase. Depois utilizei o split() para separar a frase em palavras. Criei um dicionário para armazenar a quantidade de vezes que cada palavra aparece. Utilizei o for para percorrer todas as palavras e o if para verificar se a palavra já estava no dicionário. Se já existisse, aumentava a quantidade em 1. Caso contrário, ela era adicionada com o valor 1. No final utilizei outro for para mostrar o resultado.\n",
        "\n",
        "frase = input(\"Digite uma frase: \")\n",
        "\n",
        "palavras = frase.split()\n",
        "\n",
        "contador = {}\n",
        "\n",
        "for palavra in palavras:\n",
        "    if palavra in contador:\n",
        "        contador[palavra] = contador[palavra] + 1\n",
        "    else:\n",
        "        contador[palavra] = 1\n",
        "\n",
        "for palavra in contador:\n",
        "    print(palavra, \":\", contador[palavra])"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "cC3I2BiQIqQR",
        "outputId": "026d210e-da7c-49fa-8184-2a4ae426d7d7"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite um número: 1\n",
            "O número não é primo.\n"
          ]
        }
      ],
      "source": [
        "# Exercício 18 - Número Primo\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber um número. Criei uma variável para contar quantas vezes esse número pode ser dividido sem deixar resto. Depois utilizei o for para testar todas as divisões de 1 até o número informado. Se a quantidade de divisões for igual a 2, significa que o número é primo. No final utilizei o print() para mostrar o resultado.\n",
        "\n",
        "numero = int(input(\"Digite um número: \"))\n",
        "\n",
        "divisores = 0\n",
        "\n",
        "for i in range(1, numero + 1):\n",
        "    if numero % i == 0:\n",
        "        divisores = divisores + 1\n",
        "\n",
        "if divisores == 2:\n",
        "    print(\"O número é primo.\")\n",
        "else:\n",
        "    print(\"O número não é primo.\")"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "p_GePjdUI7-C",
        "outputId": "9cc10865-95a8-4fd9-cff9-bc2872192c15"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite um número de 1 a 10: 10\n",
            "Você errou! O número era 1\n"
          ]
        }
      ],
      "source": [
        "# Exercício 19 - Jogo de Adivinhação\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei a biblioteca random para gerar um número aleatório entre 1 e 10. Depois utilizei o input() para receber o palpite do usuário e o if para verificar se o número digitado é igual ao número gerado pelo computador. No final utilizei o print() para informar se o usuário acertou ou errou.\n",
        "\n",
        "import random\n",
        "\n",
        "numero = random.randint(1, 10)\n",
        "\n",
        "palpite = int(input(\"Digite um número de 1 a 10: \"))\n",
        "\n",
        "if palpite == numero:\n",
        "    print(\"Parabéns! Você acertou!\")\n",
        "else:\n",
        "    print(\"Você errou! O número era\", numero)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "k3Doc-EQKGtw",
        "outputId": "c4e40c8b-ba69-4f47-9c3e-0c03b442c030"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Matriz original:\n",
            "[[1, 2], [3, 4]]\n",
            "Matriz transposta:\n",
            "[[1, 3], [2, 4]]\n"
          ]
        }
      ],
      "source": [
        "# Exercício 20 - Matriz Transposta\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei uma matriz com duas linhas e duas colunas. Depois criei outra matriz para armazenar a transposta. Na matriz transposta, as linhas passam a ser colunas e as colunas passam a ser linhas. No final utilizei o print() para mostrar o resultado.\n",
        "\n",
        "matriz = [\n",
        "    [1, 2],\n",
        "    [3, 4]\n",
        "]\n",
        "\n",
        "transposta = [\n",
        "    [matriz[0][0], matriz[1][0]],\n",
        "    [matriz[0][1], matriz[1][1]]\n",
        "]\n",
        "\n",
        "print(\"Matriz original:\")\n",
        "print(matriz)\n",
        "\n",
        "print(\"Matriz transposta:\")\n",
        "print(transposta)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Br3jOErKNS9v",
        "outputId": "529b0858-089c-4ce8-e625-61f3e255ac0c"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite o número que deseja encontrar: 10\n",
            "Número não encontrado\n"
          ]
        }
      ],
      "source": [
        "# Exercício 21 - Busca Binária\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei uma lista ordenada e criei uma busca binária.\n",
        "# A cada repetição, o programa verifica o elemento do meio da lista.\n",
        "# Se o valor procurado for menor, a busca continua na metade esquerda.\n",
        "# Se for maior, continua na metade direita.\n",
        "# Assim a busca fica mais rápida, pois elimina vários valores a cada passo.\n",
        "\n",
        "lista = [2, 5, 8, 12, 16, 20, 25, 30]\n",
        "\n",
        "numero = int(input(\"Digite o número que deseja encontrar: \"))\n",
        "\n",
        "inicio = 0\n",
        "fim = 7\n",
        "\n",
        "encontrado = False\n",
        "\n",
        "while inicio <= fim:\n",
        "    meio = (inicio + fim) // 2\n",
        "\n",
        "    if lista[meio] == numero:\n",
        "        encontrado = True\n",
        "        break\n",
        "\n",
        "    elif numero < lista[meio]:\n",
        "        fim = meio - 1\n",
        "\n",
        "    else:\n",
        "        inicio = meio + 1\n",
        "\n",
        "\n",
        "if encontrado:\n",
        "    print(\"Número encontrado na posição:\", meio)\n",
        "else:\n",
        "    print(\"Número não encontrado\")"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "p59gFU0INiLr",
        "outputId": "936ed509-b439-4fc5-ae1d-cfec08b5266c"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite uma mensagem: eu amo programar\n",
            "Digite o deslocamento: 5\n",
            "Mensagem criptografada: jz frt uwtlwfrfw\n"
          ]
        }
      ],
      "source": [
        "# Exercício 22 - Cifra de César\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei a cifra de César para criptografar uma mensagem.\n",
        "# Cada letra é substituída por outra que está algumas posições à frente no alfabeto.\n",
        "\n",
        "mensagem = input(\"Digite uma mensagem: \")\n",
        "\n",
        "deslocamento = int(input(\"Digite o deslocamento: \"))\n",
        "\n",
        "criptografada = \"\"\n",
        "\n",
        "for letra in mensagem:\n",
        "    if letra.isalpha():\n",
        "        codigo = ord(letra)\n",
        "        nova_letra = chr(codigo + deslocamento)\n",
        "        criptografada += nova_letra\n",
        "    else:\n",
        "        criptografada += letra\n",
        "\n",
        "print(\"Mensagem criptografada:\", criptografada)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "b8mXr0myNiwd",
        "outputId": "93084fc3-b143-42a0-d752-98d4c3466bf3"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite a mensagem criptografada: jz frt uwtlwfrfw\n",
            "Digite o deslocamento: 5\n",
            "Mensagem descriptografada: eu amo programar\n"
          ]
        }
      ],
      "source": [
        "# Exercício 23 - Descriptografar Cifra de César\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu faço o processo contrário da criptografia.\n",
        "# A letra volta a quantidade de posições informada pelo usuário.\n",
        "\n",
        "mensagem = input(\"Digite a mensagem criptografada: \")\n",
        "\n",
        "deslocamento = int(input(\"Digite o deslocamento: \"))\n",
        "\n",
        "descriptografada = \"\"\n",
        "\n",
        "for letra in mensagem:\n",
        "    if letra.isalpha():\n",
        "        codigo = ord(letra)\n",
        "        nova_letra = chr(codigo - deslocamento)\n",
        "        descriptografada += nova_letra\n",
        "    else:\n",
        "        descriptografada += letra\n",
        "\n",
        "print(\"Mensagem descriptografada:\", descriptografada)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "i8x-oYP2Ni72",
        "outputId": "8cc8aed5-6573-4f87-f0ee-3a9413df0894"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite o CPF somente com números: 47025287857\n",
            "CPF válido\n"
          ]
        }
      ],
      "source": [
        "# Exercício 24 - Validação de CPF\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber um CPF informado pelo usuário.\n",
        "# Primeiro, verifico se o CPF possui 11 números.\n",
        "# Depois, realizo os cálculos dos dois dígitos verificadores usando multiplicações\n",
        "# e pesos específicos. Por fim, comparo os dígitos calculados com os informados\n",
        "# no CPF para verificar se ele é válido ou inválido.\n",
        "\n",
        "cpf = input(\"Digite o CPF somente com números: \")\n",
        "\n",
        "if len(cpf) == 11:\n",
        "\n",
        "    soma = 0\n",
        "    peso = 10\n",
        "\n",
        "    for numero in cpf[:9]:\n",
        "        soma += int(numero) * peso\n",
        "        peso -= 1\n",
        "\n",
        "    resto = soma % 11\n",
        "\n",
        "    if resto < 2:\n",
        "        digito1 = 0\n",
        "    else:\n",
        "        digito1 = 11 - resto\n",
        "\n",
        "\n",
        "    soma = 0\n",
        "    peso = 11\n",
        "\n",
        "    for numero in cpf[:9] + str(digito1):\n",
        "        soma += int(numero) * peso\n",
        "        peso -= 1\n",
        "\n",
        "    resto = soma % 11\n",
        "\n",
        "    if resto < 2:\n",
        "        digito2 = 0\n",
        "    else:\n",
        "        digito2 = 11 - resto\n",
        "\n",
        "\n",
        "    if int(cpf[9]) == digito1 and int(cpf[10]) == digito2:\n",
        "        print(\"CPF válido\")\n",
        "    else:\n",
        "        print(\"CPF inválido\")\n",
        "\n",
        "else:\n",
        "    print(\"CPF inválido\")"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "vrv44soBS2mi",
        "outputId": "b7e16da5-557f-42e1-a7bf-9829867d28e7"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Positivos: [5, 8, 10]\n",
            "Negativos: [-3, -1]\n",
            "Zeros: [0, 0]\n"
          ]
        }
      ],
      "source": [
        "# Exercício 25 - Classificação de Números\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei três listas vazias para armazenar os números\n",
        "# positivos, negativos e iguais a zero.\n",
        "#\n",
        "# Depois, utilizei um laço de repetição for para percorrer todos os números\n",
        "# da lista principal. A cada repetição, o programa verifica o valor do número\n",
        "# usando estruturas condicionais.\n",
        "#\n",
        "# Se o número for maior que zero, ele é adicionado à lista de positivos.\n",
        "# Se for menor que zero, ele é adicionado à lista de negativos.\n",
        "# Caso o número seja igual a zero, ele é armazenado na lista de zeros.\n",
        "#\n",
        "# Ao final da execução, o programa exibe cada categoria separadamente,\n",
        "# mostrando a classificação dos números informados.\n",
        "\n",
        "numeros = [5, -3, 0, 8, -1, 0, 10]\n",
        "\n",
        "positivos = []\n",
        "negativos = []\n",
        "zeros = []\n",
        "\n",
        "for numero in numeros:\n",
        "\n",
        "    if numero > 0:\n",
        "        positivos += [numero]\n",
        "\n",
        "    elif numero < 0:\n",
        "        negativos += [numero]\n",
        "\n",
        "    else:\n",
        "        zeros += [numero]\n",
        "\n",
        "\n",
        "print(\"Positivos:\", positivos)\n",
        "print(\"Negativos:\", negativos)\n",
        "print(\"Zeros:\", zeros)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "XpTT9824AB91"
      },
      "outputs": [],
      "source": [
        "# Exercício 26 - Calculadora Simples\n",
        "\n",
        "# Explição:\n",
        "# Nesse exercício eu utilizei o input() para receber dois números\n",
        "# e a operação desejada. Depois utilizei if, elif e else para verificar\n",
        "# qual operação o usuario escolheu e realizar o cálculo correspondente.\n",
        "# Também foi feita uma verificação para impedir divisão por zero.\n",
        "\n",
        "numero1 = float(input(\" Digite o primeiro número: \"))\n",
        "numero2 = float(input(\" Digite o primeiro número: \"))\n",
        "\n",
        "operacao =  input(\"Digite a opreção (+, -, )\")"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "orGZ9A8peERz",
        "outputId": "2bc4a445-2960-4a11-c55a-e0c7902964c2"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite o primeiro número: 15\n",
            "Digite o segundo número: 10\n",
            "Digite a operação (+, -, *, /): -\n",
            "Resultado: 5.0\n"
          ]
        }
      ],
      "source": [
        "# Exercício 26 - Calculadora Simples\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber dois números e a operação\n",
        "# matemática desejada pelo usuário. Em seguida, utilizei estruturas condicionais\n",
        "# para verificar qual operação foi escolhida. Se o usuário digitar \"+\", o programa\n",
        "# realiza uma adição. Se digitar \"-\", realiza uma subtração. Se digitar \"*\",\n",
        "# realiza uma multiplicação. E se digitar \"/\", realiza uma divisão.\n",
        "# Ao final, o resultado da operação é exibido na tela.\n",
        "\n",
        "numero1 = float(input(\"Digite o primeiro número: \"))\n",
        "numero2 = float(input(\"Digite o segundo número: \"))\n",
        "\n",
        "operacao = input(\"Digite a operação (+, -, *, /): \")\n",
        "\n",
        "if operacao == \"+\":\n",
        "    resultado = numero1 + numero2\n",
        "\n",
        "elif operacao == \"-\":\n",
        "    resultado = numero1 - numero2\n",
        "\n",
        "elif operacao == \"*\":\n",
        "    resultado = numero1 * numero2\n",
        "\n",
        "elif operacao == \"/\":\n",
        "    if numero2 != 0:\n",
        "        resultado = numero1 / numero2\n",
        "    else:\n",
        "        print(\"Não é possível dividir por zero.\")\n",
        "        resultado = None\n",
        "\n",
        "else:\n",
        "    print(\"Operação inválida.\")\n",
        "    resultado = None\n",
        "\n",
        "if resultado != None:\n",
        "    print(\"Resultado:\", resultado)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "wBXGaU7ZeXMC",
        "outputId": "c2b48b2a-c634-47b9-cb3c-9fc37654dcb7"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite a primeira palavra: amor\n",
            "Digite a segunda palavra: roma\n",
            "As palavras são anagramas.\n"
          ]
        }
      ],
      "source": [
        "# Exercício 27 - Anagramas\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber duas palavras.\n",
        "# Em seguida, utilizei a função sorted() para organizar as letras das\n",
        "# duas palavras em ordem alfabética. Depois, comparei as duas listas.\n",
        "# Se elas forem iguais, significa que as palavras possuem as mesmas\n",
        "# letras e são anagramas. Caso contrário, elas não são anagramas.\n",
        "\n",
        "palavra1 = input(\"Digite a primeira palavra: \")\n",
        "\n",
        "palavra2 = input(\"Digite a segunda palavra: \")\n",
        "\n",
        "if sorted(palavra1) == sorted(palavra2):\n",
        "    print(\"As palavras são anagramas.\")\n",
        "\n",
        "else:\n",
        "    print(\"As palavras não são anagramas.\")"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 556
        },
        "id": "sqh3v0UqeXW7",
        "outputId": "28004b77-8041-4032-8c10-67c8d9024f0a"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite o nome da primeira categoria: joão\n",
            "Digite o nome da segunda categoria: maria\n",
            "Digite o nome da terceira categoria: fernanda\n",
            "Digite o valor da primeira categoria: 8\n",
            "Digite o valor da segunda categoria: 5\n",
            "Digite o valor da terceira categoria: 4\n"
          ]
        },
        {
          "data": {
            "image/png": "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\n",
            "text/plain": [
              "<Figure size 640x480 with 1 Axes>"
            ]
          },
          "metadata": {},
          "output_type": "display_data"
        }
      ],
      "source": [
        "# Exercício 28 - Gráfico de Barras\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei a biblioteca matplotlib para criar um gráfico\n",
        "# de barras com dados informados pelo usuário. Primeiro, utilizei o input()\n",
        "# para receber o nome de três categorias e seus respectivos valores.\n",
        "# Depois, armazenei essas informações em duas listas: uma para as categorias\n",
        "# e outra para os valores. Em seguida, utilizei a função bar() para criar\n",
        "# o gráfico e title() para adicionar um título. Por fim, utilizei show()\n",
        "# para exibir o gráfico na tela.\n",
        "\n",
        "import matplotlib.pyplot as plt\n",
        "\n",
        "categoria1 = input(\"Digite o nome da primeira categoria: \")\n",
        "categoria2 = input(\"Digite o nome da segunda categoria: \")\n",
        "categoria3 = input(\"Digite o nome da terceira categoria: \")\n",
        "\n",
        "valor1 = int(input(\"Digite o valor da primeira categoria: \"))\n",
        "valor2 = int(input(\"Digite o valor da segunda categoria: \"))\n",
        "valor3 = int(input(\"Digite o valor da terceira categoria: \"))\n",
        "\n",
        "categorias = [categoria1, categoria2, categoria3]\n",
        "valores = [valor1, valor2, valor3]\n",
        "\n",
        "plt.bar(categorias, valores)\n",
        "\n",
        "plt.title(\"Gráfico de Barras\")\n",
        "\n",
        "plt.show()"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "xpNSTP29hrTH",
        "outputId": "b7d44f2e-aa3e-4464-8949-48edebc065b3"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "1\n",
            "2\n",
            "Fizz\n",
            "4\n",
            "Buzz\n",
            "Fizz\n",
            "7\n",
            "8\n",
            "Fizz\n",
            "Buzz\n",
            "11\n",
            "Fizz\n",
            "13\n",
            "14\n",
            "FizzBuzz\n",
            "16\n",
            "17\n",
            "Fizz\n",
            "19\n",
            "Buzz\n",
            "Fizz\n",
            "22\n",
            "23\n",
            "Fizz\n",
            "Buzz\n",
            "26\n",
            "Fizz\n",
            "28\n",
            "29\n",
            "FizzBuzz\n",
            "31\n",
            "32\n",
            "Fizz\n",
            "34\n",
            "Buzz\n",
            "Fizz\n",
            "37\n",
            "38\n",
            "Fizz\n",
            "Buzz\n",
            "41\n",
            "Fizz\n",
            "43\n",
            "44\n",
            "FizzBuzz\n",
            "46\n",
            "47\n",
            "Fizz\n",
            "49\n",
            "Buzz\n",
            "Fizz\n",
            "52\n",
            "53\n",
            "Fizz\n",
            "Buzz\n",
            "56\n",
            "Fizz\n",
            "58\n",
            "59\n",
            "FizzBuzz\n",
            "61\n",
            "62\n",
            "Fizz\n",
            "64\n",
            "Buzz\n",
            "Fizz\n",
            "67\n",
            "68\n",
            "Fizz\n",
            "Buzz\n",
            "71\n",
            "Fizz\n",
            "73\n",
            "74\n",
            "FizzBuzz\n",
            "76\n",
            "77\n",
            "Fizz\n",
            "79\n",
            "Buzz\n",
            "Fizz\n",
            "82\n",
            "83\n",
            "Fizz\n",
            "Buzz\n",
            "86\n",
            "Fizz\n",
            "88\n",
            "89\n",
            "FizzBuzz\n",
            "91\n",
            "92\n",
            "Fizz\n",
            "94\n",
            "Buzz\n",
            "Fizz\n",
            "97\n",
            "98\n",
            "Fizz\n",
            "Buzz\n"
          ]
        }
      ],
      "source": [
        "# Exercício 29 - Números FizzBuzz\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei um laço de repetição para percorrer os números\n",
        "# de 1 até 100. Para cada número, utilizei o operador % para verificar se ele\n",
        "# é divisível por 3, por 5 ou pelos dois ao mesmo tempo. Se for divisível por\n",
        "# 3 e 5, o programa exibe \"FizzBuzz\". Se for apenas por 3, exibe \"Fizz\". Se\n",
        "# for apenas por 5, exibe \"Buzz\". Caso contrário, o próprio número é exibido.\n",
        "\n",
        "for numero in range(1, 101):\n",
        "\n",
        "    if numero % 3 == 0 and numero % 5 == 0:\n",
        "        print(\"FizzBuzz\")\n",
        "\n",
        "    elif numero % 3 == 0:\n",
        "        print(\"Fizz\")\n",
        "\n",
        "    elif numero % 5 == 0:\n",
        "        print(\"Buzz\")\n",
        "\n",
        "    else:\n",
        "        print(numero)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Qz9ZeXCjeXll",
        "outputId": "fd03b034-5a2c-4568-ab7e-1067490c8a64"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite uma letra: o\n",
            "Você acertou!\n",
            "Palavra: ____o_\n",
            "Digite uma letra: p\n",
            "Você acertou!\n",
            "Palavra: p___o_\n",
            "Digite uma letra: y\n",
            "Você acertou!\n",
            "Palavra: py__o_\n",
            "Digite uma letra: python\n",
            "Você acertou!\n",
            "Palavra: python\n",
            "Parabéns! Você venceu!\n"
          ]
        }
      ],
      "source": [
        "# Exercício 30 - Jogo da Forca\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu desenvolvi um jogo simples da forca. Primeiro,\n",
        "# defini uma palavra secreta que deverá ser descoberta pelo usuário.\n",
        "# Depois, criei uma variável para armazenar as letras que o jogador\n",
        "# acertar e outra para controlar a quantidade de tentativas.\n",
        "#\n",
        "# Utilizei um laço de repetição para permitir que o usuário continue\n",
        "# jogando enquanto ainda possuir tentativas e não descobrir a palavra.\n",
        "# A cada rodada, o programa solicita uma letra e verifica se ela faz\n",
        "# parte da palavra secreta.\n",
        "#\n",
        "# Se a letra estiver na palavra, ela é armazenada na variável que guarda\n",
        "# os acertos. Caso contrário, o jogador perde uma tentativa.\n",
        "#\n",
        "# Em seguida, utilizei um laço for para percorrer cada letra da palavra.\n",
        "# Se a letra já foi acertada, ela é exibida na tela. Caso contrário,\n",
        "# é mostrado o caractere \"_\", indicando que aquela letra ainda não foi\n",
        "# descoberta.\n",
        "#\n",
        "# O jogo termina quando o usuário descobrir todas as letras da palavra\n",
        "# ou quando as tentativas acabarem. Ao final, o programa informa se o\n",
        "# jogador venceu ou perdeu.\n",
        "\n",
        "palavra = \"python\"\n",
        "\n",
        "letras_acertadas = \"\"\n",
        "\n",
        "tentativas = 6\n",
        "\n",
        "while tentativas > 0:\n",
        "\n",
        "    letra = input(\"Digite uma letra: \")\n",
        "\n",
        "    if letra in palavra:\n",
        "        letras_acertadas += letra\n",
        "        print(\"Você acertou!\")\n",
        "\n",
        "    else:\n",
        "        tentativas -= 1\n",
        "        print(\"Você errou!\")\n",
        "        print(\"Tentativas restantes:\", tentativas)\n",
        "\n",
        "    palavra_mostrada = \"\"\n",
        "\n",
        "    for caractere in palavra:\n",
        "\n",
        "        if caractere in letras_acertadas:\n",
        "            palavra_mostrada += caractere\n",
        "\n",
        "        else:\n",
        "            palavra_mostrada += \"_\"\n",
        "\n",
        "    print(\"Palavra:\", palavra_mostrada)\n",
        "\n",
        "    if palavra_mostrada == palavra:\n",
        "        print(\"Parabéns! Você venceu!\")\n",
        "        break\n",
        "\n",
        "if palavra_mostrada != palavra:\n",
        "    print(\"Você perdeu!\")\n",
        "    print(\"A palavra era:\", palavra)\n"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "kKfWEnQdnVbI",
        "outputId": "774d7058-3367-464e-c554-d994ff4d2fe0"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Lista inicial:\n",
            "[8, 3, 10, 1, 6]\n",
            "[3, 8, 10, 1, 6]\n",
            "[3, 8, 1, 10, 6]\n",
            "[3, 8, 1, 6, 10]\n",
            "[3, 1, 8, 6, 10]\n",
            "[3, 1, 6, 8, 10]\n",
            "[1, 3, 6, 8, 10]\n",
            "Lista ordenada:\n",
            "[1, 3, 6, 8, 10]\n"
          ]
        }
      ],
      "source": [
        "# Exercício 31 - Ordenação por Bolha (Bubble Sort)\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o algoritmo Bubble Sort para ordenar uma\n",
        "# lista de números em ordem crescente. O programa compara dois números\n",
        "# vizinhos e, quando o número da esquerda é maior que o da direita,\n",
        "# eles trocam de posição. A cada troca, a lista é exibida na tela para\n",
        "# mostrar como a ordenação está acontecendo. No final, a lista fica\n",
        "# totalmente organizada em ordem crescente.\n",
        "\n",
        "numeros = [8, 3, 10, 1, 6]\n",
        "\n",
        "print(\"Lista inicial:\")\n",
        "print(numeros)\n",
        "\n",
        "for i in range(5):\n",
        "\n",
        "    for j in range(4):\n",
        "\n",
        "        if numeros[j] > numeros[j + 1]:\n",
        "\n",
        "            aux = numeros[j]\n",
        "            numeros[j] = numeros[j + 1]\n",
        "            numeros[j + 1] = aux\n",
        "\n",
        "            print(numeros)\n",
        "\n",
        "print(\"Lista ordenada:\")\n",
        "print(numeros)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "uCnrKm6JnVpN",
        "outputId": "ca6d65ab-16c1-484b-e955-810c6abc7f1c"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "  |   |  \n",
            "---------\n",
            "  |   |  \n",
            "---------\n",
            "  |   |  \n",
            "Jogador X, escolha uma posição (0 a 8): 0\n",
            "X |   |  \n",
            "---------\n",
            "  |   |  \n",
            "---------\n",
            "  |   |  \n",
            "Jogador O, escolha uma posição (0 a 8): 1\n",
            "X | O |  \n",
            "---------\n",
            "  |   |  \n",
            "---------\n",
            "  |   |  \n",
            "Jogador X, escolha uma posição (0 a 8): 2\n",
            "X | O | X\n",
            "---------\n",
            "  |   |  \n",
            "---------\n",
            "  |   |  \n",
            "Jogador O, escolha uma posição (0 a 8): 3\n",
            "X | O | X\n",
            "---------\n",
            "O |   |  \n",
            "---------\n",
            "  |   |  \n",
            "Jogador X, escolha uma posição (0 a 8): 4\n",
            "X | O | X\n",
            "---------\n",
            "O | X |  \n",
            "---------\n",
            "  |   |  \n",
            "Jogador O, escolha uma posição (0 a 8): 5\n",
            "X | O | X\n",
            "---------\n",
            "O | X | O\n",
            "---------\n",
            "  |   |  \n",
            "Jogador X, escolha uma posição (0 a 8): 6\n",
            "X | O | X\n",
            "---------\n",
            "O | X | O\n",
            "---------\n",
            "X |   |  \n",
            "Jogador X venceu!\n"
          ]
        }
      ],
      "source": [
        "# Exercício 32 - Jogo da Velha\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei um jogo da velha para dois jogadores.\n",
        "# Primeiro, criei um tabuleiro com 9 posições vazias. Depois,\n",
        "# utilizei um laço de repetição para alternar as jogadas entre os\n",
        "# jogadores X e O. Após cada jogada, o programa verifica se algum\n",
        "# jogador formou uma linha, coluna ou diagonal com três símbolos\n",
        "# iguais. Se isso acontecer, o jogador é declarado vencedor e o jogo\n",
        "# termina. Caso todas as posições sejam preenchidas sem que haja um\n",
        "# vencedor, o programa informa que deu velha (empate).\n",
        "\n",
        "tabuleiro = [\" \", \" \", \" \", \" \", \" \", \" \", \" \", \" \", \" \"]\n",
        "\n",
        "jogador = \"X\"\n",
        "\n",
        "vencedor = False\n",
        "\n",
        "for rodada in range(9):\n",
        "\n",
        "    print(tabuleiro[0], \"|\", tabuleiro[1], \"|\", tabuleiro[2])\n",
        "    print(\"---------\")\n",
        "    print(tabuleiro[3], \"|\", tabuleiro[4], \"|\", tabuleiro[5])\n",
        "    print(\"---------\")\n",
        "    print(tabuleiro[6], \"|\", tabuleiro[7], \"|\", tabuleiro[8])\n",
        "\n",
        "    posicao = int(input(\"Jogador \" + jogador + \", escolha uma posição (0 a 8): \"))\n",
        "\n",
        "    if tabuleiro[posicao] == \" \":\n",
        "\n",
        "        tabuleiro[posicao] = jogador\n",
        "\n",
        "        if (tabuleiro[0] == jogador and tabuleiro[1] == jogador and tabuleiro[2] == jogador) or \\\n",
        "           (tabuleiro[3] == jogador and tabuleiro[4] == jogador and tabuleiro[5] == jogador) or \\\n",
        "           (tabuleiro[6] == jogador and tabuleiro[7] == jogador and tabuleiro[8] == jogador) or \\\n",
        "           (tabuleiro[0] == jogador and tabuleiro[3] == jogador and tabuleiro[6] == jogador) or \\\n",
        "           (tabuleiro[1] == jogador and tabuleiro[4] == jogador and tabuleiro[7] == jogador) or \\\n",
        "           (tabuleiro[2] == jogador and tabuleiro[5] == jogador and tabuleiro[8] == jogador) or \\\n",
        "           (tabuleiro[0] == jogador and tabuleiro[4] == jogador and tabuleiro[8] == jogador) or \\\n",
        "           (tabuleiro[2] == jogador and tabuleiro[4] == jogador and tabuleiro[6] == jogador):\n",
        "\n",
        "            print(tabuleiro[0], \"|\", tabuleiro[1], \"|\", tabuleiro[2])\n",
        "            print(\"---------\")\n",
        "            print(tabuleiro[3], \"|\", tabuleiro[4], \"|\", tabuleiro[5])\n",
        "            print(\"---------\")\n",
        "            print(tabuleiro[6], \"|\", tabuleiro[7], \"|\", tabuleiro[8])\n",
        "\n",
        "            print(\"Jogador\", jogador, \"venceu!\")\n",
        "\n",
        "            vencedor = True\n",
        "\n",
        "            break\n",
        "\n",
        "        if jogador == \"X\":\n",
        "            jogador = \"O\"\n",
        "        else:\n",
        "            jogador = \"X\"\n",
        "\n",
        "    else:\n",
        "        print(\"Posição já ocupada!\")\n",
        "\n",
        "if vencedor == False:\n",
        "    print(tabuleiro[0], \"|\", tabuleiro[1], \"|\", tabuleiro[2])\n",
        "    print(\"---------\")\n",
        "    print(tabuleiro[3], \"|\", tabuleiro[4], \"|\", tabuleiro[5])\n",
        "    print(\"---------\")\n",
        "    print(tabuleiro[6], \"|\", tabuleiro[7], \"|\", tabuleiro[8])\n",
        "\n",
        "    print(\"Deu velha!\")"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "UlFTEYf7nWsd",
        "outputId": "4ceff464-e770-4408-8d22-976d06d8067b"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite a primeira palavra: amor\n",
            "Digite a segunda palavra: roma\n",
            "As palavras são anagramas.\n"
          ]
        }
      ],
      "source": [
        "# Exercício 33 - Verificação de Anagramas\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber duas palavras.\n",
        "# Depois, utilizei a função sorted() para organizar as letras das duas\n",
        "# palavras em ordem alfabética. Após isso, comparei as duas listas de letras.\n",
        "# Se elas forem iguais, significa que as palavras possuem as mesmas letras\n",
        "# em quantidades iguais, apenas em uma ordem diferente, sendo consideradas\n",
        "# anagramas. Caso contrário, as palavras não são anagramas.\n",
        "\n",
        "palavra1 = input(\"Digite a primeira palavra: \")\n",
        "\n",
        "palavra2 = input(\"Digite a segunda palavra: \")\n",
        "\n",
        "letras1 = sorted(palavra1)\n",
        "\n",
        "letras2 = sorted(palavra2)\n",
        "\n",
        "if letras1 == letras2:\n",
        "    print(\"As palavras são anagramas.\")\n",
        "\n",
        "else:\n",
        "    print(\"As palavras não são anagramas.\")"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "zspkg__bnW4Q",
        "outputId": "ca45ff70-eb0f-4766-8cdc-9274dcb4ca83"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite uma palavra ou frase: eu amo programar\n",
            "Quantidade de vogais: 7\n"
          ]
        }
      ],
      "source": [
        "# Exercício 34 - Contador de Vogais\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber uma frase ou palavra\n",
        "# digitada pelo usuário. Depois, percorri cada caractere do texto utilizando\n",
        "# um laço de repetição for. A cada letra, o programa verifica se ela é uma\n",
        "# vogal (a, e, i, o ou u). Quando encontra uma vogal, o contador é aumentado.\n",
        "# Ao final, o programa exibe a quantidade total de vogais encontradas no texto.\n",
        "\n",
        "texto = input(\"Digite uma palavra ou frase: \")\n",
        "\n",
        "contador = 0\n",
        "\n",
        "for letra in texto:\n",
        "\n",
        "    if letra == \"a\" or letra == \"e\" or letra == \"i\" or letra == \"o\" or letra == \"u\":\n",
        "\n",
        "        contador += 1\n",
        "\n",
        "print(\"Quantidade de vogais:\", contador)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "QPDRQ8W4nXAI",
        "outputId": "38876381-3206-4ffc-9996-3403dfb16155"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite um número limite: 50\n",
            "Sequência de Fibonacci:\n",
            "0\n",
            "1\n",
            "0 + 1 = 1\n",
            "1 + 1 = 2\n",
            "1 + 2 = 3\n",
            "2 + 3 = 5\n",
            "3 + 5 = 8\n",
            "5 + 8 = 13\n",
            "8 + 13 = 21\n",
            "13 + 21 = 34\n"
          ]
        }
      ],
      "source": [
        "# Exercício 35 - Números Fibonacci Até N\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber um número limite.\n",
        "# Depois, criei duas variáveis para guardar os primeiros valores da sequência\n",
        "# de Fibonacci. A cada repetição, o programa soma os dois valores anteriores\n",
        "# para gerar o próximo número. Além de exibir a sequência, o programa também\n",
        "# mostra as contas realizadas para chegar em cada resultado.\n",
        "\n",
        "limite = int(input(\"Digite um número limite: \"))\n",
        "\n",
        "anterior = 0\n",
        "atual = 1\n",
        "\n",
        "print(\"Sequência de Fibonacci:\")\n",
        "\n",
        "print(anterior)\n",
        "print(atual)\n",
        "\n",
        "while anterior + atual <= limite:\n",
        "\n",
        "    proximo = anterior + atual\n",
        "\n",
        "    print(anterior, \"+\", atual, \"=\", proximo)\n",
        "\n",
        "    anterior = atual\n",
        "\n",
        "    atual = proximo"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "ZDJeg_h_uSOZ",
        "outputId": "a7b602de-9f25-414a-a2ec-c0bfcdc82dbf"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite o tamanho da senha: 10\n",
            "Senha gerada: VTivZnGsSP\n"
          ]
        }
      ],
      "source": [
        "# Exercício 36 - Gerador de Senhas\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei um gerador de senhas aleatórias utilizando letras\n",
        "# e números. Primeiro, criei uma lista contendo todos os caracteres que podem\n",
        "# ser usados na senha.\n",
        "#\n",
        "# Depois, utilizei o input() para receber o tamanho da senha que o usuário\n",
        "# deseja criar. Em seguida, utilizei um laço de repetição for para escolher\n",
        "# aleatoriamente cada caractere que fará parte da senha.\n",
        "#\n",
        "# A cada repetição, um novo caractere é escolhido e adicionado à variável\n",
        "# que armazena a senha. Ao final, o programa exibe a senha gerada.\n",
        "\n",
        "import random\n",
        "\n",
        "caracteres = \"abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789\"\n",
        "\n",
        "tamanho = int(input(\"Digite o tamanho da senha: \"))\n",
        "\n",
        "senha = \"\"\n",
        "\n",
        "for i in range(tamanho):\n",
        "\n",
        "    caractere = random.choice(caracteres)\n",
        "\n",
        "    senha += caractere\n",
        "\n",
        "print(\"Senha gerada:\", senha)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "tb0cpylNuSc5",
        "outputId": "bf45ccd0-66c3-4731-a557-e3bc3230afb1"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite um número: 5\n",
            "Fatorial de 5 é: 120\n"
          ]
        }
      ],
      "source": [
        "# Exercício 37 - Funções Recursivas\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei uma função recursiva para calcular o fatorial\n",
        "# de um número. Uma função recursiva é uma função que chama ela mesma\n",
        "# durante sua execução.\n",
        "#\n",
        "# Primeiro, o programa recebe um número informado pelo usuário.\n",
        "# Depois, a função verifica se o número é igual a 0 ou 1, pois nesses casos\n",
        "# o resultado do fatorial é 1, encerrando a repetição.\n",
        "#\n",
        "# Caso o número seja maior que 1, a função multiplica o número pelo fatorial\n",
        "# do número anterior, chamando ela mesma novamente até chegar ao caso final.\n",
        "# Ao terminar os cálculos, o resultado do fatorial é exibido na tela.\n",
        "\n",
        "def fatorial(numero):\n",
        "\n",
        "    if numero == 0 or numero == 1:\n",
        "\n",
        "        return 1\n",
        "\n",
        "    else:\n",
        "\n",
        "        return numero * fatorial(numero - 1)\n",
        "\n",
        "\n",
        "numero = int(input(\"Digite um número: \"))\n",
        "\n",
        "resultado = fatorial(numero)\n",
        "\n",
        "print(\"Fatorial de\", numero, \"é:\", resultado)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "wFmugn5AuSf5",
        "outputId": "e80383a8-9f61-46c7-d8bc-3e2c5226031a"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite um texto: eu amo programar\n",
            "Quantidade de palavras: 3\n"
          ]
        }
      ],
      "source": [
        "# Exercício 38 - Contar Palavras em Texto\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber um texto digitado pelo\n",
        "# usuário. Depois, utilizei a função split() para separar o texto em palavras.\n",
        "# Cada palavra separada é armazenada dentro de uma lista.\n",
        "#\n",
        "# Em seguida, utilizei um laço de repetição for para passar por cada palavra\n",
        "# da lista. A cada repetição, o contador aumenta 1, contando a quantidade de\n",
        "# palavras existentes no texto. No final, o programa exibe o total de palavras.\n",
        "\n",
        "texto = input(\"Digite um texto: \")\n",
        "\n",
        "palavras = texto.split()\n",
        "\n",
        "contador = 0\n",
        "\n",
        "for palavra in palavras:\n",
        "\n",
        "    contador += 1\n",
        "\n",
        "print(\"Quantidade de palavras:\", contador)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0YQBkhamuT_y",
        "outputId": "5b340381-0dde-41c1-ce2b-eda4d526dad0"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite o valor do primeiro dado (1 a 6): 5\n",
            "Digite o valor do segundo dado (1 a 6): 4\n",
            "Resultado do primeiro dado: 5\n",
            "Resultado do segundo dado: 4\n",
            "Soma dos dados: 9\n"
          ]
        }
      ],
      "source": [
        "# Exercício 39 - Jogo de Dados\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu simulei o lançamento de dois dados.\n",
        "# Como não foi utilizado o recurso de números aleatórios, o usuário informa\n",
        "# o valor de cada dado. Depois, o programa soma os dois valores e exibe\n",
        "# o resultado final.\n",
        "\n",
        "dado1 = int(input(\"Digite o valor do primeiro dado (1 a 6): \"))\n",
        "\n",
        "dado2 = int(input(\"Digite o valor do segundo dado (1 a 6): \"))\n",
        "\n",
        "soma = dado1 + dado2\n",
        "\n",
        "print(\"Resultado do primeiro dado:\", dado1)\n",
        "\n",
        "print(\"Resultado do segundo dado:\", dado2)\n",
        "\n",
        "print(\"Soma dos dados:\", soma)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "background_save": true,
          "base_uri": "https://localhost:8080/"
        },
        "id": "MGLHunfMuUIV",
        "outputId": "698629dc-acf6-4f97-ed1a-b85815d98c6b"
      },
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "\n",
            "1 - Adicionar item\n",
            "2 - Remover item\n",
            "3 - Listar compras\n",
            "4 - Sair\n",
            "Item adicionado!\n",
            "\n",
            "1 - Adicionar item\n",
            "2 - Remover item\n",
            "3 - Listar compras\n",
            "4 - Sair\n",
            "Lista de compras:\n",
            "leite\n",
            "\n",
            "1 - Adicionar item\n",
            "2 - Remover item\n",
            "3 - Listar compras\n",
            "4 - Sair\n"
          ]
        }
      ],
      "source": [
        "# Exercício 40 - Lista de Compras\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei um programa para gerenciar uma lista de compras.\n",
        "# Primeiro, criei uma lista vazia onde os produtos adicionados pelo usuário\n",
        "# serão armazenados.\n",
        "#\n",
        "# Depois, utilizei um laço de repetição para manter o programa funcionando,\n",
        "# permitindo que o usuário escolha entre adicionar um item, remover um item\n",
        "# ou visualizar a lista de compras.\n",
        "#\n",
        "# Quando o usuário escolhe adicionar, o produto é colocado na lista.\n",
        "# Quando escolhe remover, o programa procura o item e remove da lista.\n",
        "# Na opção listar, todos os produtos cadastrados são exibidos na tela.\n",
        "\n",
        "compras = []\n",
        "\n",
        "opcao = 0\n",
        "\n",
        "while opcao != 4:\n",
        "\n",
        "    print(\"\\n1 - Adicionar item\")\n",
        "    print(\"2 - Remover item\")\n",
        "    print(\"3 - Listar compras\")\n",
        "    print(\"4 - Sair\")\n",
        "\n",
        "    opcao = int(input(\"Escolha uma opção: \"))\n",
        "\n",
        "    if opcao == 1:\n",
        "\n",
        "        item = input(\"Digite o item que deseja adicionar: \")\n",
        "\n",
        "        compras.append(item)\n",
        "\n",
        "        print(\"Item adicionado!\")\n",
        "\n",
        "    elif opcao == 2:\n",
        "\n",
        "        item = input(\"Digite o item que deseja remover: \")\n",
        "\n",
        "        if item in compras:\n",
        "\n",
        "            compras.remove(item)\n",
        "\n",
        "            print(\"Item removido!\")\n",
        "\n",
        "        else:\n",
        "\n",
        "            print(\"Item não encontrado!\")\n",
        "\n",
        "    elif opcao == 3:\n",
        "\n",
        "        print(\"Lista de compras:\")\n",
        "\n",
        "        for item in compras:\n",
        "\n",
        "            print(item)\n",
        "\n",
        "    elif opcao == 4:\n",
        "\n",
        "        print(\"Programa encerrado!\")\n",
        "\n",
        "    else:\n",
        "\n",
        "        print(\"Opção inválida!\")"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Exercício 41 - Remover Duplicatas\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei um programa que remove os números repetidos\n",
        "# de uma lista. Primeiro, criei uma lista contendo alguns números,\n",
        "# inclusive alguns repetidos. Depois, criei uma nova lista vazia para\n",
        "# armazenar apenas os números que ainda não apareceram.\n",
        "#\n",
        "# Em seguida, utilizei um laço de repetição para percorrer todos os\n",
        "# elementos da lista original. A cada repetição, o programa verifica\n",
        "# se o número já está na nova lista. Se não estiver, ele é adicionado\n",
        "# utilizando a concatenação de listas. Ao final, a nova lista contém\n",
        "# apenas os números sem repetição.\n",
        "\n",
        "# Lista original\n",
        "numeros = [5, 2, 8, 2, 4, 5, 9, 8, 1]\n",
        "\n",
        "# Lista sem duplicatas\n",
        "sem_duplicatas = []\n",
        "\n",
        "# Percorre a lista\n",
        "for numero in numeros:\n",
        "\n",
        "    # Verifica se o número ainda não existe na nova lista\n",
        "    if numero not in sem_duplicatas:\n",
        "\n",
        "        # Adiciona o número utilizando concatenação\n",
        "        sem_duplicatas = sem_duplicatas + [numero]\n",
        "\n",
        "print(\"Lista original:\")\n",
        "print(numeros)\n",
        "\n",
        "print(\"Lista sem duplicatas:\")\n",
        "print(sem_duplicatas)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "_40FzQZSXb2E",
        "outputId": "6d583155-a00a-475d-a23f-4299033ea679"
      },
      "execution_count": 1,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Lista original:\n",
            "[5, 2, 8, 2, 4, 5, 9, 8, 1]\n",
            "Lista sem duplicatas:\n",
            "[5, 2, 8, 4, 9, 1]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Exercício 42 - Números Primos até N\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber um número informado\n",
        "# pelo usuário. Depois, utilizei um laço de repetição para verificar todos\n",
        "# os números de 2 até o número digitado. Para cada número, o programa verifica\n",
        "# se ele possui algum divisor além de 1 e dele mesmo. Se não possuir,\n",
        "# ele é considerado um número primo e é exibido na tela.\n",
        "\n",
        "# Recebe do usuário o número limite\n",
        "limite = int(input(\"Digite um número: \"))\n",
        "\n",
        "# Exibe uma mensagem informando o que será mostrado\n",
        "print(\"Números primos até\", limite, \":\")\n",
        "\n",
        "# Percorre todos os números de 2 até o número informado\n",
        "for numero in range(2, limite + 1):\n",
        "\n",
        "    # No início, considera que o número é primo\n",
        "    primo = True\n",
        "\n",
        "    # Testa todos os possíveis divisores\n",
        "    for divisor in range(2, numero):\n",
        "\n",
        "        # Verifica se a divisão é exata\n",
        "        if numero % divisor == 0:\n",
        "\n",
        "            # Se encontrar um divisor, o número não é primo\n",
        "            primo = False\n",
        "\n",
        "    # Se continuar sendo primo, exibe o número\n",
        "    if primo == True:\n",
        "\n",
        "        print(numero)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "PEuGfGaIXcBi",
        "outputId": "5e355c48-265e-47f3-9aa7-d1051dfaa795"
      },
      "execution_count": 5,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite um número: 50\n",
            "Números primos até 50 :\n",
            "2\n",
            "3\n",
            "5\n",
            "7\n",
            "11\n",
            "13\n",
            "17\n",
            "19\n",
            "23\n",
            "29\n",
            "31\n",
            "37\n",
            "41\n",
            "43\n",
            "47\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Exercício 43 - Conversor de Unidades\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu criei um conversor de unidades de comprimento.\n",
        "# Primeiro, o programa recebe um valor em metros informado pelo usuário.\n",
        "# Depois, apresenta um menu para que o usuário escolha para qual unidade\n",
        "# deseja converter. Em seguida, realiza o cálculo correspondente e exibe\n",
        "# o resultado na tela.\n",
        "\n",
        "# Recebe a quantidade em metros\n",
        "metros = float(input(\"Digite a quantidade em metros: \"))\n",
        "\n",
        "# Exibe o menu de opções\n",
        "print(\"1 - Centímetros\")\n",
        "print(\"2 - Milímetros\")\n",
        "print(\"3 - Quilômetros\")\n",
        "\n",
        "# Recebe a opção escolhida\n",
        "opcao = int(input(\"Escolha uma opção: \"))\n",
        "\n",
        "# Verifica se o usuário escolheu centímetros\n",
        "if opcao == 1:\n",
        "\n",
        "    # Converte metros para centímetros\n",
        "    resultado = metros * 100\n",
        "\n",
        "    # Exibe o resultado\n",
        "    print(metros, \"metros =\", resultado, \"centímetros\")\n",
        "\n",
        "# Verifica se o usuário escolheu milímetros\n",
        "elif opcao == 2:\n",
        "\n",
        "    # Converte metros para milímetros\n",
        "    resultado = metros * 1000\n",
        "\n",
        "    # Exibe o resultado\n",
        "    print(metros, \"metros =\", resultado, \"milímetros\")\n",
        "\n",
        "# Verifica se o usuário escolheu quilômetros\n",
        "elif opcao == 3:\n",
        "\n",
        "    # Converte metros para quilômetros\n",
        "    resultado = metros / 1000\n",
        "\n",
        "    # Exibe o resultado\n",
        "    print(metros, \"metros =\", resultado, \"quilômetros\")\n",
        "\n",
        "# Caso o usuário digite uma opção inválida\n",
        "else:\n",
        "\n",
        "    print(\"Opção inválida!\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "_WTZpjmLXcKm",
        "outputId": "0ac3e523-89d0-41f6-d33b-190fbc373cf9"
      },
      "execution_count": 8,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite a quantidade em metros: 10\n",
            "1 - Centímetros\n",
            "2 - Milímetros\n",
            "3 - Quilômetros\n",
            "Escolha uma opção: 3\n",
            "10.0 metros = 0.01 quilômetros\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Exercício 44 - Fibonacci em Nível\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber a quantidade de\n",
        "# termos da sequência de Fibonacci que o usuário deseja visualizar.\n",
        "# Depois, criei duas variáveis para armazenar os dois primeiros números\n",
        "# da sequência. Em seguida, utilizei um laço de repetição para gerar\n",
        "# a quantidade de termos informada pelo usuário. A cada repetição,\n",
        "# o programa exibe o número atual, calcula o próximo número da sequência\n",
        "# e atualiza os valores para continuar o processo.\n",
        "\n",
        "# Recebe a quantidade de termos da sequência\n",
        "quantidade = int(input(\"Digite a quantidade de termos: \"))\n",
        "\n",
        "# Primeiro número da sequência\n",
        "anterior = 0\n",
        "\n",
        "# Segundo número da sequência\n",
        "atual = 1\n",
        "\n",
        "# Exibe uma mensagem\n",
        "print(\"Sequência de Fibonacci:\")\n",
        "\n",
        "# Repete a quantidade de vezes informada\n",
        "for i in range(quantidade):\n",
        "\n",
        "    # Exibe o número atual da sequência\n",
        "    print(anterior)\n",
        "\n",
        "    # Calcula o próximo número\n",
        "    proximo = anterior + atual\n",
        "\n",
        "    # Atualiza o valor do número anterior\n",
        "    anterior = atual\n",
        "\n",
        "    # Atualiza o valor do número atual\n",
        "    atual = proximo"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "4zie_T1LXcZw",
        "outputId": "76e1b25f-5f16-4cb3-b2fb-47de18878b2b"
      },
      "execution_count": 9,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite a quantidade de termos: 10\n",
            "Sequência de Fibonacci:\n",
            "0\n",
            "1\n",
            "1\n",
            "2\n",
            "3\n",
            "5\n",
            "8\n",
            "13\n",
            "21\n",
            "34\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Exercício 45 - Par ou Ímpar em Lista\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei uma lista de números e percorri todos os\n",
        "# seus elementos utilizando um laço de repetição. Para cada número,\n",
        "# utilizei o operador % (resto da divisão) para verificar se ele é\n",
        "# par ou ímpar.\n",
        "#\n",
        "# Se o resto da divisão por 2 for igual a 0, o número é par.\n",
        "# Caso contrário, o número é ímpar. Ao final, o programa informa a\n",
        "# classificação de cada número da lista.\n",
        "\n",
        "# Lista de números\n",
        "numeros = [8, 3, 10, 7, 12, 5, 18, 9]\n",
        "\n",
        "# Percorre todos os números da lista\n",
        "for numero in numeros:\n",
        "\n",
        "    # Verifica se o número é par\n",
        "    if numero % 2 == 0:\n",
        "\n",
        "        # Exibe que o número é par\n",
        "        print(numero, \"é par\")\n",
        "\n",
        "    # Caso contrário, o número é ímpar\n",
        "    else:\n",
        "\n",
        "        # Exibe que o número é ímpar\n",
        "        print(numero, \"é ímpar\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "dQthOsRVXcj1",
        "outputId": "be3471e5-9ba4-4704-d0ee-c746dbee3dfa"
      },
      "execution_count": 10,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "8 é par\n",
            "3 é ímpar\n",
            "10 é par\n",
            "7 é ímpar\n",
            "12 é par\n",
            "5 é ímpar\n",
            "18 é par\n",
            "9 é ímpar\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Exercício 46 - Calcular Média e Desvio Padrão\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei uma lista de números para calcular a média\n",
        "# e o desvio padrão. Primeiro, somei todos os números da lista e dividi\n",
        "# pela quantidade de elementos para encontrar a média.\n",
        "#\n",
        "# Depois, calculei a diferença entre cada número e a média. Essa diferença\n",
        "# foi elevada ao quadrado e somada. Em seguida, dividi essa soma pela\n",
        "# quantidade de números para encontrar a variância.\n",
        "#\n",
        "# Por último, calculei a raiz quadrada da variância utilizando o operador\n",
        "# de potência (** 0.5), encontrando o desvio padrão.\n",
        "\n",
        "# Lista de números\n",
        "numeros = [5, 8, 10, 6, 9]\n",
        "\n",
        "# Variável para armazenar a soma dos números\n",
        "soma = 0\n",
        "\n",
        "# Variável para contar a quantidade de números\n",
        "quantidade = 0\n",
        "\n",
        "# Percorre toda a lista\n",
        "for numero in numeros:\n",
        "\n",
        "    # Soma os números\n",
        "    soma = soma + numero\n",
        "\n",
        "    # Conta quantos números existem\n",
        "    quantidade = quantidade + 1\n",
        "\n",
        "# Calcula a média\n",
        "media = soma / quantidade\n",
        "\n",
        "# Exibe a média\n",
        "print(\"Média:\", media)\n",
        "\n",
        "# Variável para armazenar a soma das diferenças ao quadrado\n",
        "soma_diferencas = 0\n",
        "\n",
        "# Percorre novamente todos os números\n",
        "for numero in numeros:\n",
        "\n",
        "    # Calcula a diferença entre o número e a média\n",
        "    diferenca = numero - media\n",
        "\n",
        "    # Eleva a diferença ao quadrado\n",
        "    quadrado = diferenca ** 2\n",
        "\n",
        "    # Soma os quadrados\n",
        "    soma_diferencas = soma_diferencas + quadrado\n",
        "\n",
        "# Calcula a variância\n",
        "variancia = soma_diferencas / quantidade\n",
        "\n",
        "# Calcula o desvio padrão (raiz quadrada da variância)\n",
        "desvio = variancia ** 0.5\n",
        "\n",
        "# Exibe o desvio padrão\n",
        "print(\"Desvio padrão:\", desvio)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "oA9wE5twajOA",
        "outputId": "1f81115a-665d-4cb0-af84-d37d7e3207f5"
      },
      "execution_count": 1,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Média: 7.6\n",
            "Desvio padrão: 1.8547236990991407\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Exercício 47 - Contar Números em Lista\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei uma lista de números e contei quantas vezes\n",
        "# cada número aparece. Primeiro, percorri toda a lista. Para evitar contar\n",
        "# o mesmo número mais de uma vez, verifiquei se ele já havia sido contado.\n",
        "# Se ainda não tivesse sido contado, percorri novamente a lista para contar\n",
        "# quantas vezes ele aparecia. No final, exibi o número e a quantidade de\n",
        "# vezes que ele foi encontrado.\n",
        "\n",
        "# Lista de números\n",
        "numeros = [2, 5, 2, 8, 5, 2, 9, 8, 1]\n",
        "\n",
        "# Lista para guardar os números que já foram contados\n",
        "contados = []\n",
        "\n",
        "# Percorre todos os números da lista\n",
        "for numero in numeros:\n",
        "\n",
        "    # Verifica se o número ainda não foi contado\n",
        "    if numero not in contados:\n",
        "\n",
        "        # Variável para contar quantas vezes o número aparece\n",
        "        contador = 0\n",
        "\n",
        "        # Percorre novamente toda a lista\n",
        "        for valor in numeros:\n",
        "\n",
        "            # Verifica se o número é igual ao valor da lista\n",
        "            if numero == valor:\n",
        "\n",
        "                # Aumenta o contador\n",
        "                contador = contador + 1\n",
        "\n",
        "        # Exibe o resultado\n",
        "        print(numero, \"aparece\", contador, \"vez(es).\")\n",
        "\n",
        "        # Guarda o número para não contá-lo novamente\n",
        "        contados = contados + [numero]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "yzYTWx6-ajVE",
        "outputId": "e402363e-04b6-433f-9cc5-0eb56e80d70e"
      },
      "execution_count": 2,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "2 aparece 3 vez(es).\n",
            "5 aparece 2 vez(es).\n",
            "8 aparece 2 vez(es).\n",
            "9 aparece 1 vez(es).\n",
            "1 aparece 1 vez(es).\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Exercício 48 - Ordenação por Inserção (Insertion Sort)\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o algoritmo Insertion Sort para ordenar\n",
        "# uma lista de números em ordem crescente.\n",
        "#\n",
        "# O algoritmo funciona como se estivéssemos organizando cartas na mão.\n",
        "# Ele começa considerando que o primeiro número já está na posição correta.\n",
        "# Depois, pega o próximo número e o compara com os anteriores.\n",
        "# Se o número for menor, os outros números são deslocados para a direita\n",
        "# até que seja encontrada a posição correta para inseri-lo.\n",
        "#\n",
        "# Esse processo é repetido até que toda a lista esteja ordenada.\n",
        "\n",
        "# Lista de números\n",
        "numeros = [8, 3, 10, 1, 6]\n",
        "\n",
        "# Exibe a lista antes da ordenação\n",
        "print(\"Lista inicial:\")\n",
        "print(numeros)\n",
        "\n",
        "# Percorre a lista a partir do segundo elemento\n",
        "for i in range(1, len(numeros)):\n",
        "\n",
        "    # Guarda o número que será inserido\n",
        "    atual = numeros[i]\n",
        "\n",
        "    # Guarda a posição anterior\n",
        "    j = i - 1\n",
        "\n",
        "    # Enquanto existir posição anterior\n",
        "    # e o número anterior for maior que o atual\n",
        "    while j >= 0 and numeros[j] > atual:\n",
        "\n",
        "        # Desloca o número maior uma posição para a direita\n",
        "        numeros[j + 1] = numeros[j]\n",
        "\n",
        "        # Vai para a posição anterior\n",
        "        j = j - 1\n",
        "\n",
        "    # Coloca o número na posição correta\n",
        "    numeros[j + 1] = atual\n",
        "\n",
        "    # Exibe a lista após cada inserção\n",
        "    print(numeros)\n",
        "\n",
        "# Exibe a lista ordenada\n",
        "print(\"Lista ordenada:\")\n",
        "print(numeros)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Z1rLsq76ajd3",
        "outputId": "aac5c3b2-4ae4-4e79-9e1e-b439ac0f4804"
      },
      "execution_count": 4,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Lista inicial:\n",
            "[8, 3, 10, 1, 6]\n",
            "[3, 8, 10, 1, 6]\n",
            "[3, 8, 10, 1, 6]\n",
            "[1, 3, 8, 10, 6]\n",
            "[1, 3, 6, 8, 10]\n",
            "Lista ordenada:\n",
            "[1, 3, 6, 8, 10]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Exercício 49 - Soma dos Dígitos\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber um número inteiro\n",
        "# informado pelo usuário. Depois, percorri cada dígito desse número\n",
        "# utilizando um laço de repetição.\n",
        "#\n",
        "# A cada repetição, o programa converte o dígito para inteiro e soma\n",
        "# esse valor em uma variável acumuladora. No final, o programa exibe\n",
        "# a soma de todos os dígitos do número.\n",
        "\n",
        "# Recebe um número do usuário\n",
        "numero = input(\"Digite um número inteiro: \")\n",
        "\n",
        "# Variável que armazenará a soma dos dígitos\n",
        "soma = 0\n",
        "\n",
        "# Percorre cada dígito do número\n",
        "for digito in numero:\n",
        "\n",
        "    # Converte o dígito para inteiro e soma\n",
        "    soma = soma + int(digito)\n",
        "\n",
        "# Exibe o número digitado\n",
        "print(\"Número digitado:\", numero)\n",
        "\n",
        "# Exibe a soma dos dígitos\n",
        "print(\"Soma dos dígitos:\", soma)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "tnixN1ExajqD",
        "outputId": "f9447f5e-d36d-48ef-b295-95877d2db166"
      },
      "execution_count": 6,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite um número inteiro: 456\n",
            "Número digitado: 456\n",
            "Soma dos dígitos: 15\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Exercício 50 - Cálculo de Frequência de Letras\n",
        "\n",
        "# Explicação:\n",
        "# Nesse exercício eu utilizei o input() para receber uma palavra ou frase\n",
        "# digitada pelo usuário. Depois, percorri cada letra do texto para descobrir\n",
        "# quantas vezes ela aparece.\n",
        "#\n",
        "# Para não contar a mesma letra mais de uma vez, utilizei uma lista para\n",
        "# armazenar as letras que já foram verificadas. Em seguida, percorri o texto\n",
        "# novamente para contar quantas vezes cada letra aparece.\n",
        "#\n",
        "# No final, o programa exibe cada letra e a quantidade de vezes que ela foi\n",
        "# encontrada no texto.\n",
        "\n",
        "# Recebe uma palavra ou frase\n",
        "texto = input(\"Digite uma palavra ou frase: \")\n",
        "\n",
        "# Lista para guardar as letras que já foram contadas\n",
        "letras_contadas = []\n",
        "\n",
        "# Percorre cada caractere do texto\n",
        "for letra in texto:\n",
        "\n",
        "    # Ignora os espaços\n",
        "    if letra != \" \":\n",
        "\n",
        "        # Verifica se a letra ainda não foi contada\n",
        "        if letra not in letras_contadas:\n",
        "\n",
        "            # Variável para contar quantas vezes a letra aparece\n",
        "            contador = 0\n",
        "\n",
        "            # Percorre novamente todo o texto\n",
        "            for caractere in texto:\n",
        "\n",
        "                # Verifica se a letra é igual ao caractere\n",
        "                if letra == caractere:\n",
        "\n",
        "                    # Aumenta o contador\n",
        "                    contador = contador + 1\n",
        "\n",
        "            # Exibe o resultado\n",
        "            print(letra, \"aparece\", contador, \"vez(es).\")\n",
        "\n",
        "            # Guarda a letra para não contá-la novamente\n",
        "            letras_contadas = letras_contadas + [letra]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "bBnBBHRbajz6",
        "outputId": "9b77d0d7-6be3-4347-c396-9b5b1928c81a"
      },
      "execution_count": 7,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite uma palavra ou frase: banana\n",
            "b aparece 1 vez(es).\n",
            "a aparece 3 vez(es).\n",
            "n aparece 2 vez(es).\n"
          ]
        }
      ]
    }
  ],
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyNxbQ+jqJxnHwdfvFCF6XNa",
      "include_colab_link": true
    },
    "kernelspec": {
      "display_name": "Python 3",
      "name": "python3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "nbformat": 4,
  "nbformat_minor": 0
}
