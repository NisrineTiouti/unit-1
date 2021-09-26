{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "name": "programming_task_1",
      "provenance": [],
      "authorship_tag": "ABX9TyOKTZOYmzMiyallqt0H7T8K",
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
        "<a href=\"https://colab.research.google.com/github/NisrineTiouti/unit-1/blob/main/programming_task_1.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "vEsxv3Bw6QIk",
        "outputId": "716c00aa-bfbc-4db4-9b3a-4acee0664b6d"
      },
      "source": [
        "#Ask the user for 2 numbers a and b\n",
        "#Check if one of them is 10 or if their sum is 10 \n",
        "list = [a, b]\n",
        "print(\"Enter 2 numbers: \")\n",
        "a = input()\n",
        "b = input()\n",
        "\n",
        "if '10' in list:\n",
        "  print(f\"Makes10({a}, {b})-->True\")\n",
        "  if '10' not in list:\n",
        "    print(f\"Makes10({a}, {b})-->False\")\n",
        "  \n",
        "elif int(a) + int(b) == 10:\n",
        "  print(f\"Makes10({a}, {b})--> True\")\n",
        "else:\n",
        "  print(f\"Makes10({a}, {b})--> False\")\n",
        "\n",
        "\n",
        " \n"
      ],
      "execution_count": 31,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Enter 2 numbers: \n",
            "7\n",
            "8\n",
            "Makes10(7, 8)--> False\n"
          ]
        }
      ]
    }
  ]
}