{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyM1xijf0szQMfzEbgiae5rD",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/teuxx/aula-programacao/blob/main/README.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "#ex.05 transformando mm em polegada  "
      ],
      "metadata": {
        "id": "UregZihuIPTh"
      }
    },
    {
      "cell_type": "code",
      "execution_count": 4,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "UV0XLTVCIEaZ",
        "outputId": "6dbc8c18-5f39-4e44-efa1-96d1eb637acb"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "digite valor em polegada:1\n",
            "o valor em mm é: 25.4\n"
          ]
        }
      ],
      "source": [
        "p = float (input(\"digite valor em polegada:\"))\n",
        "mm = p*25.4\n",
        "\n",
        "#mostra na tela\n",
        "print (\"o valor em mm é:\", mm)"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "#importar pi"
      ],
      "metadata": {
        "id": "R1gRowsmOy5R"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "from math import pi\n",
        "\n",
        "#esfera\n",
        "r = float(input(\"digite o valor do raio\"))\n",
        "\n",
        "v = (4/3) *pi * (r**3)\n",
        "\n",
        "#valor total de acordo com o usuario\n",
        "print (\"o valor da esfera é:\", v)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "fLaNfNZOO3Dq",
        "outputId": "8b05c999-4ffc-4006-e16e-4cf9b4c35971"
      },
      "execution_count": 12,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "digite o valor do raio2\n",
            "o valor da esfera é:.2f 33.510321638291124\n"
          ]
        }
      ]
    }
  ]
}