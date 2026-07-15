{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "mount_file_id": "1e33zHv-I_9cGnidw9LvaJYMuPlJeOO7w",
      "authorship_tag": "ABX9TyPrvNlj+0SD/uho04QQzuU7",
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
        "<a href=\"https://colab.research.google.com/github/GD-Chandrakar/Python_AIML_PEP/blob/main/Python_in_AIML.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "##Day 1 (INTRODUCTION IN PYTHON)"
      ],
      "metadata": {
        "id": "Aii6WUdwrhSv"
      }
    },
    {
      "cell_type": "code",
      "execution_count": 2,
      "metadata": {
        "id": "Sh-4nHV5CQ1J"
      },
      "outputs": [],
      "source": [
        "# PYTHON WAS INVENTED BY GUIDO VAN ROSSUM ON 20 FEB 1991\n",
        "# IT IS A HIGH LEVEL PARTIAL OOP(OBJECT ORIENTED PROGRAMMING LANGUAGE)\n",
        "# 50% --> POP(PROCEDURE ORIENTED PROGRAMMING)\n",
        "# 50% --> OOP(OBJECT ORIENTED PROGRAMMING)\n",
        "# Python is an Dynamically typed programming language(there is no need to explicitly diclare the datatype)\n",
        "# Python user interpreter for executing its code\n",
        "# python follow strict indentation (following spaces).\n",
        "# Python is platform-independent\n",
        "# Python is case-sensitive\n",
        "# Python has simple and easy syntax while compare to other programming languages\n",
        "# Pthon uses interpreter for executing its code.\n",
        "# Python has no memory specificness,its memory is Infinite\n",
        "# Python will not allow memory wastage(thats why  pyhton has no pointers).\n",
        "\n",
        "\n",
        "# Comments in Python:\n",
        "# python consist of only single-line comment which is denoted by '#' ''' --> Document strings(doc string)\n",
        "\n",
        "# Variable:\n",
        "# Variable is a containter which is used to hold any type of data.\n",
        "# A name given to a memory location is nothing to a variable.\n",
        "\n",
        "\n",
        "# Introduction to datatype in Pyhton\n",
        "\n",
        "# int ,float ,complex,boolean,None,string,list,tuple,set\n",
        "# ambigoity\n",
        "\n",
        "# In python when a user take a input it automatically convert into string.\n",
        "# sequence allow you to store multiple datatype\n",
        "# string is a collection of characters which is enclosed in between single '',doubel\"\",or triple inverted comas,\n",
        "# python doest have character datatype insted , if you trying to we have assing a single character or multiple character it is a string\n",
        "# In python  whenever we are using input to take input from the user automatically that data converted to string datatype/.\n",
        "\n",
        "\n"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# # Methods of list\n",
        "# l=[1,2.3,9+2j,\"Hello\",True]\n",
        "# l2=[4,2,5,6,15,45,102,234,77]\n",
        "# l.append(10)#adding element at the end of the list\n",
        "# print(l)\n",
        "# l.insert(3,4) # it adds the element at the specific positionof the list according to the index\n",
        "# print(l)\n",
        "# l.remove(1)#it remove specific element from the list\n",
        "# print(l)\n",
        "# l.pop()#it delete/remove the last element from the list\n",
        "# print(l)\n",
        "# count=l.count(1)#it counts no.of times the element exists in the list\n",
        "# print(count)\n",
        "# l.reverse()#it prints the list in reverse order\n",
        "# print(l)\n",
        "# l2.sort() #it prints the elements of the list in ascending order\n",
        "# print(l2)\n",
        "# print(l[0])#it delete all the elements of the list\n",
        "# l.clear()\n",
        "# print(l)\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "1J2BuKQBFs6h"
      },
      "execution_count": 3,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Day 2"
      ],
      "metadata": {
        "id": "WAGu06L91vmD"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "import sys\n",
        "\n",
        "# Write a program in python to reverse the element of the list without using reverse function\n",
        "list=[1,5,9,7,3]\n",
        "sys.stdout.write(str(list) + '\\n')\n",
        "rev_list = list[::-1]\n",
        "sys.stdout.write(str(rev_list) + '\\n')\n",
        "\n",
        "#write a program in python even number in 20\n",
        "for i in range(1,21):\n",
        "  if(i%2==0):\n",
        "   sys.stdout.write(str(i) + '\\n')\n"
      ],
      "metadata": {
        "id": "qgGoYs6xNfkE",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "ab376cae-4db7-4b4d-fd08-2cc89e9a2bea"
      },
      "execution_count": 256,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[1, 5, 9, 7, 3]\n",
            "[3, 7, 9, 5, 1]\n",
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
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "dict = {\n",
        "    'names': ['hi', 'hello'],\n",
        "    'age': [11, 12]\n",
        "}\n",
        "print(dict['names'])\n",
        "print(dict['age'])"
      ],
      "metadata": {
        "id": "26Ll-iLWTgPz",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "c26ed5e7-55dc-4808-b59f-5db716056bfa"
      },
      "execution_count": 257,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "['hi', 'hello']\n",
            "[11, 12]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# write a program in python which takes 1 member from user from 0 to 9 and prints in the word.\n",
        "# if the number is outside from the range from 0 to 9 than it exist from the range.\n",
        "\n",
        "num=int(input(\"enter the number:\"))\n",
        "dict = {0:'zero',\n",
        "        1:'one',\n",
        "        2:'two',\n",
        "        3:'three',\n",
        "        4:'four',\n",
        "        5:'five',\n",
        "        6:'six',\n",
        "        7:'seven',\n",
        "        8:'eight',\n",
        "        9:'nine'}\n",
        "\n",
        "\n",
        "if num in dict:\n",
        "  print(dict[num])\n",
        "else:\n",
        "  print(\"The number is outside the range from 0 to 9.\")"
      ],
      "metadata": {
        "id": "a1kI5OiSW9Oc",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "291b1039-2788-49a6-8f2a-462eab567523"
      },
      "execution_count": 258,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "enter the number:67\n",
            "The number is outside the range from 0 to 9.\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# write a program in Python that checks if the given number is an Armstrong number\n",
        "\n",
        "num = int(input(\"Enter a number: \"))\n",
        "\n",
        "original = num\n",
        "sum = 0\n",
        "\n",
        "digits = len(str(num))\n",
        "\n",
        "while num > 0:\n",
        "    digit = num % 10\n",
        "    sum += digit ** digits\n",
        "    num = num // 10\n",
        "\n",
        "if sum == original:\n",
        "    print(original, \"is an Armstrong number\")\n",
        "else:\n",
        "    print(original, \"is not an Armstrong number\")"
      ],
      "metadata": {
        "id": "V9j3eGQlZU5V",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "01c97df2-ecd0-45d5-a65f-66716e9ff3cb"
      },
      "execution_count": 259,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Enter a number: 97\n",
            "97 is not an Armstrong number\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Day -3 (Numpy,Pandas)"
      ],
      "metadata": {
        "id": "gbjZxblprVXA"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "# Numpy stands for numerical python.\n",
        "# It is python library used for first numerical computations.\n",
        "# It provide support for multi dimensional arrays and mathematical operations.\n",
        "# Advantages : Numpy array is faster than python list.\n",
        "            # It uses less memory.\n",
        "            # It supports vectorised operations.\n",
        "            # It is usefull for AI&Ml and Data science.\n",
        "\n",
        "#Create  an 1D array\n",
        "import numpy as np\n",
        "a= np.array([1,2,3])\n",
        "print(type(a))\n",
        "print(a.ndim)\n",
        "print(a.size)\n",
        "print(a.shape)\n",
        "print(a.dtype)\n",
        "print(a)"
      ],
      "metadata": {
        "id": "itpPMXp7a_pf",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "b1c08272-5a72-4111-f045-357346a95b94"
      },
      "execution_count": 260,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'numpy.ndarray'>\n",
            "1\n",
            "3\n",
            "(3,)\n",
            "int64\n",
            "[1 2 3]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "b=np.array([{1,2},{3,4},{5,6}])\n",
        "print(type(b))\n",
        "print(b.ndim)\n",
        "print(b.size)\n",
        "print(b.shape)\n",
        "print(b.dtype)\n",
        "print(b)\n"
      ],
      "metadata": {
        "id": "Mt6ES-YLtc8w",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "8089c8e7-7389-4cf3-ac4b-d5b37699e3de"
      },
      "execution_count": 261,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'numpy.ndarray'>\n",
            "1\n",
            "3\n",
            "(3,)\n",
            "object\n",
            "[{1, 2} {3, 4} {5, 6}]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "c=np.array([{1,2,3},{4,5,6},{7,8,9}])\n",
        "print(type(c))\n",
        "print(c.ndim)\n",
        "print(c.size)\n",
        "print(c.shape)\n",
        "print(c.dtype)\n",
        "print(c)"
      ],
      "metadata": {
        "id": "E_TLOMxOt3WM",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "cc67647f-a7f1-4dd8-b03c-c6af1bad3189"
      },
      "execution_count": 262,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'numpy.ndarray'>\n",
            "1\n",
            "3\n",
            "(3,)\n",
            "object\n",
            "[{1, 2, 3} {4, 5, 6} {8, 9, 7}]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "d=np.zeros((3,3))\n",
        "print(d)"
      ],
      "metadata": {
        "id": "QfM_LceC7kTe",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "0455dceb-890e-42a2-c8be-fd158e9e6e47"
      },
      "execution_count": 263,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[0. 0. 0.]\n",
            " [0. 0. 0.]\n",
            " [0. 0. 0.]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Print numpy identityy matrix of size 3\n",
        "arr3 = np.eye(3)\n",
        "print(arr3)"
      ],
      "metadata": {
        "id": "SU_jsemPvwqA",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "02179ce7-c1dc-4c94-e7a3-ed786725b740"
      },
      "execution_count": 264,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[1. 0. 0.]\n",
            " [0. 1. 0.]\n",
            " [0. 0. 1.]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Print elements from 1 to 10 of numpy array.\n",
        "arr=np.arange(1,11)\n",
        "print(arr)"
      ],
      "metadata": {
        "id": "pz4c_mNAv47q",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "ee2e2cde-d645-4bb9-c4c4-b3e6c38e6e25"
      },
      "execution_count": 265,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[ 1  2  3  4  5  6  7  8  9 10]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Linspace\n",
        "arr=np.linspace(1,10,5)\n",
        "print(arr)"
      ],
      "metadata": {
        "id": "AiQ41uSbwkGL",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "d7961d34-4718-4fb8-d1e4-aefded6f6955"
      },
      "execution_count": 266,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[ 1.    3.25  5.5   7.75 10.  ]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "c=np.array([{1,2,3},{4,5,6},{7,8,9}])\n",
        "\n",
        "print(type(c))\n",
        "print(c.ndim)\n",
        "print(c.size)\n",
        "print(c.shape)\n",
        "print(c.dtype)\n"
      ],
      "metadata": {
        "id": "N_uqokb5w3tG",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "899028f7-d668-4d08-a3c2-e583f8182f04"
      },
      "execution_count": 267,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'numpy.ndarray'>\n",
            "1\n",
            "3\n",
            "(3,)\n",
            "object\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "m=np.array([1,2,3,4,5])\n",
        "n=np.array([6,7,8,9,10])\n",
        "\n",
        "print(m+n)\n",
        "print(m-n)\n",
        "print(m*n)\n",
        "print(m/n)"
      ],
      "metadata": {
        "id": "qPff-Bnyx9d3",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "2bbf312c-f843-4f3d-ae99-6dfdc9ab96e6"
      },
      "execution_count": 268,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[ 7  9 11 13 15]\n",
            "[-5 -5 -5 -5 -5]\n",
            "[ 6 14 24 36 50]\n",
            "[0.16666667 0.28571429 0.375      0.44444444 0.5       ]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#aggregate  functions\n",
        "arr7=np.array([10,56,78,87,34,56,72])\n",
        "print(np.sum(arr7))\n",
        "print(np.min(arr7))\n",
        "print(np.max(arr7))\n",
        "print(np.mean(arr7))\n",
        "print(np.median(arr7))\n",
        "print(np.std(arr7))"
      ],
      "metadata": {
        "id": "2bcWU6KMysuW",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "f913e399-41c7-4167-8a96-34eae8b6d7a4"
      },
      "execution_count": 269,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "393\n",
            "10\n",
            "87\n",
            "56.142857142857146\n",
            "56.0\n",
            "24.787258082839784\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "arr = np.arange(1, 10)\n",
        "print(arr.reshape(3,3))"
      ],
      "metadata": {
        "id": "gXRA-o6hyxZv",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "18082a7d-7833-4664-a999-7fd7311eee55"
      },
      "execution_count": 271,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[1 2 3]\n",
            " [4 5 6]\n",
            " [7 8 9]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "arr9=np.array([10,56,78,90,34,56,76,12,48])\n",
        "print(arr9[4])\n",
        "print(arr9[2:5])\n",
        "print(arr9[2:8:2])\n",
        "print(arr9[-3:-1])\n",
        "print(arr9[::2])"
      ],
      "metadata": {
        "id": "EcYwEDvAzUBd",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "545d8015-cae7-4fda-a7ab-331c25bb8827"
      },
      "execution_count": 272,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "34\n",
            "[78 90 34]\n",
            "[78 34 76]\n",
            "[76 12]\n",
            "[10 78 34 76 48]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "## Introduction to pandas\n"
      ],
      "metadata": {
        "id": "PlhCYJnr0Zqy"
      },
      "execution_count": 273,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "#boolean indexing\n",
        "arr=np.array([10,56,78,87,34,56,72,12,48])\n",
        "print(arr[arr>50])\n",
        "print(arr[arr%2==0])"
      ],
      "metadata": {
        "id": "bf1SBCT21euD",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "18364d38-dc91-46a9-ebde-6f8c22a2fe5c"
      },
      "execution_count": 274,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[56 78 87 56 72]\n",
            "[10 56 78 34 56 72 12 48]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# pyhton is python library  which is used for data analysis and manipulation\n",
        "# it provide to measure data structure.\n",
        "# series 1D ,data frames 2D\n",
        "# series[1D]\n",
        "# a series is a 1D label array\n",
        "\n",
        "import pandas as pd\n",
        "\n",
        "a = pd.Series([1,2,3,4,4,5,6])\n",
        "\n",
        "print(a)"
      ],
      "metadata": {
        "id": "XuPvkAZm1kpz",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "e7a79927-4915-45ed-d1a0-262c7840837e"
      },
      "execution_count": 275,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0    1\n",
            "1    2\n",
            "2    3\n",
            "3    4\n",
            "4    4\n",
            "5    5\n",
            "6    6\n",
            "dtype: int64\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "import pandas as pd\n",
        "\n",
        "a = pd.Series([100, 200, 300], index=[\"A\", \"B\", \"C\"])\n",
        "\n",
        "print(a)\n",
        "print(a['A'])"
      ],
      "metadata": {
        "id": "L_ioD-3c9Z9z",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "ad404a34-50c1-4bf6-dcea-2e97a2b16fc9"
      },
      "execution_count": 276,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "A    100\n",
            "B    200\n",
            "C    300\n",
            "dtype: int64\n",
            "100\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "import pandas as pd\n",
        "data = {'maths':35, 'science':89, 'English':94}\n",
        "s = pd.Series(data)\n",
        "print(s)"
      ],
      "metadata": {
        "id": "cjwl-kca-DRo",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "82e1ba54-1c7e-46c6-eefd-44fb68a3c335"
      },
      "execution_count": 277,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "maths      35\n",
            "science    89\n",
            "English    94\n",
            "dtype: int64\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "s = pd.Series([1,2,3,4,5])\n",
        "print(s + 7)\n",
        "print(s * 2)"
      ],
      "metadata": {
        "id": "fbWJQNK8-M97",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "85cef3fe-c826-4882-ffaf-2e81618fc834"
      },
      "execution_count": 278,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0     8\n",
            "1     9\n",
            "2    10\n",
            "3    11\n",
            "4    12\n",
            "dtype: int64\n",
            "0     2\n",
            "1     4\n",
            "2     6\n",
            "3     8\n",
            "4    10\n",
            "dtype: int64\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# DataFrames\n",
        "# A dataframe is a two dimensional data which is consisting of rows and columns.\n",
        "data = {\n",
        "    'name': ['hi', 'hello', 'world'],\n",
        "    'age': [12, 13, 14],\n",
        "    'city': ['Vizay', 'hyd', 'banglore']\n",
        "}\n",
        "\n",
        "a = pd.DataFrame(data)\n",
        "\n",
        "print(a)"
      ],
      "metadata": {
        "id": "Tr4BCHTu-QLB",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "dd3febd5-799d-4848-94ad-a6f5984bcd56"
      },
      "execution_count": 279,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "    name  age      city\n",
            "0     hi   12     Vizay\n",
            "1  hello   13       hyd\n",
            "2  world   14  banglore\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Create dataframe from list\n",
        "data = [\n",
        "    [\"Rahul\", 20, \"Delhi\"],\n",
        "    [\"Aman\", 21, \"Mumbai\"],\n",
        "    [\"Priya\", 19, \"Pune\"]\n",
        "]\n",
        "\n",
        "df = pd.DataFrame(data, columns=[\"Name\", \"Age\", \"City\"])\n",
        "print(df)"
      ],
      "metadata": {
        "id": "hl49J57X-Uvp",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "73fefd81-8fbe-4f16-c90a-ab8cbf42911e"
      },
      "execution_count": 280,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "    Name  Age    City\n",
            "0  Rahul   20   Delhi\n",
            "1   Aman   21  Mumbai\n",
            "2  Priya   19    Pune\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Day 4"
      ],
      "metadata": {
        "id": "KThe0Nbf6EBR"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "import pandas as pd\n",
        "df=pd.read_csv(\"/content/AI_Impact_on_Jobs_2030.csv\")\n",
        "print(df)\n",
        "df.head()"
      ],
      "metadata": {
        "id": "C4N0_I6D-q3q",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 1000
        },
        "outputId": "6b8613ca-d803-4fa5-844a-fa389be5a0f8"
      },
      "execution_count": 254,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "     Employee_ID              Job_Title    Industry    Country  \\\n",
            "0     AIJ-100000          Data Engineer  Healthcare      Japan   \n",
            "1     AIJ-100001     Healthcare Analyst      Retail         UK   \n",
            "2     AIJ-100002          HR Specialist   Education     Canada   \n",
            "3     AIJ-100003  Cybersecurity Analyst  Government         UK   \n",
            "4     AIJ-100004     Healthcare Analyst   Education        UAE   \n",
            "...          ...                    ...         ...        ...   \n",
            "2995  AIJ-102995         Data Scientist   Education      India   \n",
            "2996  AIJ-102996          Data Engineer  Healthcare        UAE   \n",
            "2997  AIJ-102997        DevOps Engineer      Energy   Pakistan   \n",
            "2998  AIJ-102998         Data Scientist  Government  Australia   \n",
            "2999  AIJ-102999          HR Specialist      Retail    Germany   \n",
            "\n",
            "     Education_Level  Years_Experience  AI_Replacement_Risk  \\\n",
            "0                PhD                 1                 0.25   \n",
            "1           Bachelor                24                 0.73   \n",
            "2        High School                21                 0.80   \n",
            "3           Bachelor                 5                 0.29   \n",
            "4                PhD                20                 0.11   \n",
            "...              ...               ...                  ...   \n",
            "2995        Bachelor                 0                 0.62   \n",
            "2996             PhD                 4                 0.52   \n",
            "2997     High School                 7                 0.72   \n",
            "2998        Bachelor                19                 0.82   \n",
            "2999          Master                 9                 0.68   \n",
            "\n",
            "      Future_Demand_Score Remote_Work_Possibility  Average_Salary_USD  \\\n",
            "0                    0.78                     Yes              207392   \n",
            "1                    0.33                      No              140785   \n",
            "2                    0.69                     Yes              124800   \n",
            "3                    0.94                      No              199878   \n",
            "4                    0.92                      No              178682   \n",
            "...                   ...                     ...                 ...   \n",
            "2995                 0.27                  Hybrid              202565   \n",
            "2996                 0.57                     Yes               37215   \n",
            "2997                 0.70                      No               55179   \n",
            "2998                 0.76                  Hybrid              125291   \n",
            "2999                 0.44                      No              152792   \n",
            "\n",
            "                                        Required_Skills Automation_Level  \\\n",
            "0                  Python, Communication, Deep Learning              Low   \n",
            "1     Deep Learning, Azure, Communication, TensorFlo...              Low   \n",
            "2     Kubernetes, Cloud Computing, TensorFlow, SQL, ...           Medium   \n",
            "3     Excel, Kubernetes, Prompt Engineering, Leadership           Medium   \n",
            "4            SQL, Leadership, TensorFlow, Cybersecurity              Low   \n",
            "...                                                 ...              ...   \n",
            "2995  Azure, Project Management, Cloud Computing, Cy...           Medium   \n",
            "2996                     Communication, PyTorch, Docker              Low   \n",
            "2997                  TensorFlow, Excel, Python, Docker           Medium   \n",
            "2998      Cybersecurity, Cloud Computing, Deep Learning           Medium   \n",
            "2999           Kubernetes, Cybersecurity, Communication              Low   \n",
            "\n",
            "      Job_Growth_2030  Work_Hours_Per_Week Company_Size AI_Tool_Usage  \\\n",
            "0                   3                   37   Enterprise          High   \n",
            "1                  -5                   42      Startup      Moderate   \n",
            "2                  -5                   57      Startup           Low   \n",
            "3                   7                   59   Enterprise          High   \n",
            "4                   6                   34      Startup          High   \n",
            "...               ...                  ...          ...           ...   \n",
            "2995               36                   59   Enterprise      Moderate   \n",
            "2996               17                   45      Startup           Low   \n",
            "2997               34                   35      Startup           Low   \n",
            "2998               21                   47      Startup      Moderate   \n",
            "2999               32                   44       Medium      Moderate   \n",
            "\n",
            "      Performance_Score Upskilling_Needed  Job_Satisfaction Hiring_Trend_2026  \n",
            "0                  2.08               Yes              3.86           Growing  \n",
            "1                  4.54                No              4.23           Growing  \n",
            "2                  3.14                No              3.54            Stable  \n",
            "3                  3.67                No              4.37         Declining  \n",
            "4                  3.68                No              3.99            Stable  \n",
            "...                 ...               ...               ...               ...  \n",
            "2995               4.54               Yes              1.27            Stable  \n",
            "2996               2.71                No              2.56            Stable  \n",
            "2997               4.88               Yes              3.17         Declining  \n",
            "2998               3.59               Yes              3.78            Stable  \n",
            "2999               3.29                No              1.36           Growing  \n",
            "\n",
            "[3000 rows x 20 columns]\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "  Employee_ID              Job_Title    Industry Country Education_Level  \\\n",
              "0  AIJ-100000          Data Engineer  Healthcare   Japan             PhD   \n",
              "1  AIJ-100001     Healthcare Analyst      Retail      UK        Bachelor   \n",
              "2  AIJ-100002          HR Specialist   Education  Canada     High School   \n",
              "3  AIJ-100003  Cybersecurity Analyst  Government      UK        Bachelor   \n",
              "4  AIJ-100004     Healthcare Analyst   Education     UAE             PhD   \n",
              "\n",
              "   Years_Experience  AI_Replacement_Risk  Future_Demand_Score  \\\n",
              "0                 1                 0.25                 0.78   \n",
              "1                24                 0.73                 0.33   \n",
              "2                21                 0.80                 0.69   \n",
              "3                 5                 0.29                 0.94   \n",
              "4                20                 0.11                 0.92   \n",
              "\n",
              "  Remote_Work_Possibility  Average_Salary_USD  \\\n",
              "0                     Yes              207392   \n",
              "1                      No              140785   \n",
              "2                     Yes              124800   \n",
              "3                      No              199878   \n",
              "4                      No              178682   \n",
              "\n",
              "                                     Required_Skills Automation_Level  \\\n",
              "0               Python, Communication, Deep Learning              Low   \n",
              "1  Deep Learning, Azure, Communication, TensorFlo...              Low   \n",
              "2  Kubernetes, Cloud Computing, TensorFlow, SQL, ...           Medium   \n",
              "3  Excel, Kubernetes, Prompt Engineering, Leadership           Medium   \n",
              "4         SQL, Leadership, TensorFlow, Cybersecurity              Low   \n",
              "\n",
              "   Job_Growth_2030  Work_Hours_Per_Week Company_Size AI_Tool_Usage  \\\n",
              "0                3                   37   Enterprise          High   \n",
              "1               -5                   42      Startup      Moderate   \n",
              "2               -5                   57      Startup           Low   \n",
              "3                7                   59   Enterprise          High   \n",
              "4                6                   34      Startup          High   \n",
              "\n",
              "   Performance_Score Upskilling_Needed  Job_Satisfaction Hiring_Trend_2026  \n",
              "0               2.08               Yes              3.86           Growing  \n",
              "1               4.54                No              4.23           Growing  \n",
              "2               3.14                No              3.54            Stable  \n",
              "3               3.67                No              4.37         Declining  \n",
              "4               3.68                No              3.99            Stable  "
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-3f096026-411e-45fd-8da0-b3d2b6aafaf6\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>Employee_ID</th>\n",
              "      <th>Job_Title</th>\n",
              "      <th>Industry</th>\n",
              "      <th>Country</th>\n",
              "      <th>Education_Level</th>\n",
              "      <th>Years_Experience</th>\n",
              "      <th>AI_Replacement_Risk</th>\n",
              "      <th>Future_Demand_Score</th>\n",
              "      <th>Remote_Work_Possibility</th>\n",
              "      <th>Average_Salary_USD</th>\n",
              "      <th>Required_Skills</th>\n",
              "      <th>Automation_Level</th>\n",
              "      <th>Job_Growth_2030</th>\n",
              "      <th>Work_Hours_Per_Week</th>\n",
              "      <th>Company_Size</th>\n",
              "      <th>AI_Tool_Usage</th>\n",
              "      <th>Performance_Score</th>\n",
              "      <th>Upskilling_Needed</th>\n",
              "      <th>Job_Satisfaction</th>\n",
              "      <th>Hiring_Trend_2026</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>AIJ-100000</td>\n",
              "      <td>Data Engineer</td>\n",
              "      <td>Healthcare</td>\n",
              "      <td>Japan</td>\n",
              "      <td>PhD</td>\n",
              "      <td>1</td>\n",
              "      <td>0.25</td>\n",
              "      <td>0.78</td>\n",
              "      <td>Yes</td>\n",
              "      <td>207392</td>\n",
              "      <td>Python, Communication, Deep Learning</td>\n",
              "      <td>Low</td>\n",
              "      <td>3</td>\n",
              "      <td>37</td>\n",
              "      <td>Enterprise</td>\n",
              "      <td>High</td>\n",
              "      <td>2.08</td>\n",
              "      <td>Yes</td>\n",
              "      <td>3.86</td>\n",
              "      <td>Growing</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>AIJ-100001</td>\n",
              "      <td>Healthcare Analyst</td>\n",
              "      <td>Retail</td>\n",
              "      <td>UK</td>\n",
              "      <td>Bachelor</td>\n",
              "      <td>24</td>\n",
              "      <td>0.73</td>\n",
              "      <td>0.33</td>\n",
              "      <td>No</td>\n",
              "      <td>140785</td>\n",
              "      <td>Deep Learning, Azure, Communication, TensorFlo...</td>\n",
              "      <td>Low</td>\n",
              "      <td>-5</td>\n",
              "      <td>42</td>\n",
              "      <td>Startup</td>\n",
              "      <td>Moderate</td>\n",
              "      <td>4.54</td>\n",
              "      <td>No</td>\n",
              "      <td>4.23</td>\n",
              "      <td>Growing</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>AIJ-100002</td>\n",
              "      <td>HR Specialist</td>\n",
              "      <td>Education</td>\n",
              "      <td>Canada</td>\n",
              "      <td>High School</td>\n",
              "      <td>21</td>\n",
              "      <td>0.80</td>\n",
              "      <td>0.69</td>\n",
              "      <td>Yes</td>\n",
              "      <td>124800</td>\n",
              "      <td>Kubernetes, Cloud Computing, TensorFlow, SQL, ...</td>\n",
              "      <td>Medium</td>\n",
              "      <td>-5</td>\n",
              "      <td>57</td>\n",
              "      <td>Startup</td>\n",
              "      <td>Low</td>\n",
              "      <td>3.14</td>\n",
              "      <td>No</td>\n",
              "      <td>3.54</td>\n",
              "      <td>Stable</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>3</th>\n",
              "      <td>AIJ-100003</td>\n",
              "      <td>Cybersecurity Analyst</td>\n",
              "      <td>Government</td>\n",
              "      <td>UK</td>\n",
              "      <td>Bachelor</td>\n",
              "      <td>5</td>\n",
              "      <td>0.29</td>\n",
              "      <td>0.94</td>\n",
              "      <td>No</td>\n",
              "      <td>199878</td>\n",
              "      <td>Excel, Kubernetes, Prompt Engineering, Leadership</td>\n",
              "      <td>Medium</td>\n",
              "      <td>7</td>\n",
              "      <td>59</td>\n",
              "      <td>Enterprise</td>\n",
              "      <td>High</td>\n",
              "      <td>3.67</td>\n",
              "      <td>No</td>\n",
              "      <td>4.37</td>\n",
              "      <td>Declining</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>4</th>\n",
              "      <td>AIJ-100004</td>\n",
              "      <td>Healthcare Analyst</td>\n",
              "      <td>Education</td>\n",
              "      <td>UAE</td>\n",
              "      <td>PhD</td>\n",
              "      <td>20</td>\n",
              "      <td>0.11</td>\n",
              "      <td>0.92</td>\n",
              "      <td>No</td>\n",
              "      <td>178682</td>\n",
              "      <td>SQL, Leadership, TensorFlow, Cybersecurity</td>\n",
              "      <td>Low</td>\n",
              "      <td>6</td>\n",
              "      <td>34</td>\n",
              "      <td>Startup</td>\n",
              "      <td>High</td>\n",
              "      <td>3.68</td>\n",
              "      <td>No</td>\n",
              "      <td>3.99</td>\n",
              "      <td>Stable</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-3f096026-411e-45fd-8da0-b3d2b6aafaf6')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-3f096026-411e-45fd-8da0-b3d2b6aafaf6 button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-3f096026-411e-45fd-8da0-b3d2b6aafaf6');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "variable_name": "df",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 3000,\n  \"fields\": [\n    {\n      \"column\": \"Employee_ID\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 3000,\n        \"samples\": [\n          \"AIJ-101801\",\n          \"AIJ-101190\",\n          \"AIJ-101817\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Job_Title\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 20,\n        \"samples\": [\n          \"Data Engineer\",\n          \"Software Developer\",\n          \"Prompt Engineer\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Industry\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 10,\n        \"samples\": [\n          \"Finance\",\n          \"Retail\",\n          \"Media\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Country\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 10,\n        \"samples\": [\n          \"USA\",\n          \"UK\",\n          \"Pakistan\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Education_Level\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 4,\n        \"samples\": [\n          \"Bachelor\",\n          \"Master\",\n          \"PhD\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Years_Experience\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 7,\n        \"min\": 0,\n        \"max\": 25,\n        \"num_unique_values\": 26,\n        \"samples\": [\n          6,\n          9,\n          1\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"AI_Replacement_Risk\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0.26129317494803583,\n        \"min\": 0.05,\n        \"max\": 0.95,\n        \"num_unique_values\": 91,\n        \"samples\": [\n          0.94,\n          0.27,\n          0.79\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Future_Demand_Score\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0.22667372803631888,\n        \"min\": 0.2,\n        \"max\": 0.99,\n        \"num_unique_values\": 80,\n        \"samples\": [\n          0.7,\n          0.78,\n          0.96\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Remote_Work_Possibility\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"Yes\",\n          \"No\",\n          \"Hybrid\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Average_Salary_USD\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 55405,\n        \"min\": 30221,\n        \"max\": 219998,\n        \"num_unique_values\": 2970,\n        \"samples\": [\n          154244,\n          94241,\n          31064\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Required_Skills\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 2937,\n        \"samples\": [\n          \"Kubernetes, Communication, Deep Learning\",\n          \"SQL, Cloud Computing, Project Management\",\n          \"TensorFlow, Python, Project Management, Data Visualization, Prompt Engineering, Communication\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Automation_Level\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"Low\",\n          \"Medium\",\n          \"High\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Job_Growth_2030\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 16,\n        \"min\": -10,\n        \"max\": 45,\n        \"num_unique_values\": 56,\n        \"samples\": [\n          3,\n          22,\n          9\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Work_Hours_Per_Week\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 8,\n        \"min\": 30,\n        \"max\": 60,\n        \"num_unique_values\": 31,\n        \"samples\": [\n          58,\n          30,\n          40\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Company_Size\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"Enterprise\",\n          \"Startup\",\n          \"Medium\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"AI_Tool_Usage\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"High\",\n          \"Moderate\",\n          \"Low\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Performance_Score\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0.8733747194584259,\n        \"min\": 2.0,\n        \"max\": 5.0,\n        \"num_unique_values\": 301,\n        \"samples\": [\n          3.93,\n          2.96,\n          2.04\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Upskilling_Needed\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 2,\n        \"samples\": [\n          \"No\",\n          \"Yes\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Job_Satisfaction\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 1.1463613829688888,\n        \"min\": 1.0,\n        \"max\": 5.0,\n        \"num_unique_values\": 401,\n        \"samples\": [\n          4.95,\n          4.84\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Hiring_Trend_2026\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"Growing\",\n          \"Stable\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 254
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.tail()"
      ],
      "metadata": {
        "id": "cK9n9VKKzxcp",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 143
        },
        "outputId": "8b8993bc-dcef-4d06-c1c8-358f53583ec3"
      },
      "execution_count": 28,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "    Name  Age    City\n",
              "0  Rahul   20   Delhi\n",
              "1   Aman   21  Mumbai\n",
              "2  Priya   19    Pune"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-54816d88-10a0-4343-981c-405060ccd90b\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>Name</th>\n",
              "      <th>Age</th>\n",
              "      <th>City</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>Rahul</td>\n",
              "      <td>20</td>\n",
              "      <td>Delhi</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>Aman</td>\n",
              "      <td>21</td>\n",
              "      <td>Mumbai</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>Priya</td>\n",
              "      <td>19</td>\n",
              "      <td>Pune</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-54816d88-10a0-4343-981c-405060ccd90b')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-54816d88-10a0-4343-981c-405060ccd90b button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-54816d88-10a0-4343-981c-405060ccd90b');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 3,\n  \"fields\": [\n    {\n      \"column\": \"Name\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"Rahul\",\n          \"Aman\",\n          \"Priya\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Age\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 1,\n        \"min\": 19,\n        \"max\": 21,\n        \"num_unique_values\": 3,\n        \"samples\": [\n          20,\n          21,\n          19\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"City\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"Delhi\",\n          \"Mumbai\",\n          \"Pune\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 28
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.shape"
      ],
      "metadata": {
        "id": "67TU5iybxy0H",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "af4d062c-708e-4a5f-919a-d66b17dd1b4b"
      },
      "execution_count": 29,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "(3, 3)"
            ]
          },
          "metadata": {},
          "execution_count": 29
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.info()"
      ],
      "metadata": {
        "id": "OlP7zYxbzMuE",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "f2b95234-49a3-4cfe-b40e-ac25b4cd791d"
      },
      "execution_count": 30,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'pandas.core.frame.DataFrame'>\n",
            "RangeIndex: 3 entries, 0 to 2\n",
            "Data columns (total 3 columns):\n",
            " #   Column  Non-Null Count  Dtype \n",
            "---  ------  --------------  ----- \n",
            " 0   Name    3 non-null      object\n",
            " 1   Age     3 non-null      int64 \n",
            " 2   City    3 non-null      object\n",
            "dtypes: int64(1), object(2)\n",
            "memory usage: 204.0+ bytes\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.describe()"
      ],
      "metadata": {
        "id": "lhKr0bELzQk-",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 300
        },
        "outputId": "ce5cc2c7-7970-4226-f721-27672a30aff1"
      },
      "execution_count": 31,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "        Age\n",
              "count   3.0\n",
              "mean   20.0\n",
              "std     1.0\n",
              "min    19.0\n",
              "25%    19.5\n",
              "50%    20.0\n",
              "75%    20.5\n",
              "max    21.0"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-db76a3bb-161d-4e1e-9deb-e4a6a86cb85c\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>Age</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>count</th>\n",
              "      <td>3.0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>mean</th>\n",
              "      <td>20.0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>std</th>\n",
              "      <td>1.0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>min</th>\n",
              "      <td>19.0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>25%</th>\n",
              "      <td>19.5</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>50%</th>\n",
              "      <td>20.0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>75%</th>\n",
              "      <td>20.5</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>max</th>\n",
              "      <td>21.0</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-db76a3bb-161d-4e1e-9deb-e4a6a86cb85c')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-db76a3bb-161d-4e1e-9deb-e4a6a86cb85c button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-db76a3bb-161d-4e1e-9deb-e4a6a86cb85c');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 8,\n  \"fields\": [\n    {\n      \"column\": \"Age\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 8.370867850553404,\n        \"min\": 1.0,\n        \"max\": 21.0,\n        \"num_unique_values\": 7,\n        \"samples\": [\n          3.0,\n          20.0,\n          20.5\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 31
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(df.columns)"
      ],
      "metadata": {
        "id": "IT7C38I3zSwK",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "5c92bb10-ad36-4b86-c4a0-8e173485375d"
      },
      "execution_count": 32,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Index(['Name', 'Age', 'City'], dtype='object')\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(df.dtypes)"
      ],
      "metadata": {
        "id": "S9WjnAYFziUc",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "6bd48fca-d857-49ea-b197-bb3a2413c68e"
      },
      "execution_count": 33,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Name    object\n",
            "Age      int64\n",
            "City    object\n",
            "dtype: object\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(df[\"Future_Demand_Score\"])"
      ],
      "metadata": {
        "id": "PBuTne8G0QAE",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "d2ebaf83-4002-4e8d-b25e-781554c75376"
      },
      "execution_count": 255,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0       0.78\n",
            "1       0.33\n",
            "2       0.69\n",
            "3       0.94\n",
            "4       0.92\n",
            "        ... \n",
            "2995    0.27\n",
            "2996    0.57\n",
            "2997    0.70\n",
            "2998    0.76\n",
            "2999    0.44\n",
            "Name: Future_Demand_Score, Length: 3000, dtype: float64\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#loc()\n",
        "#iloc()\n",
        "#write a program\n",
        "# The primary difference between the loc and iloc in python is loc uses label indexing to sleect data\n",
        "# where as iloc integer position based indexing.\n",
        "df.loc[0]\n"
      ],
      "metadata": {
        "id": "XkMOpULy1NTN",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 178
        },
        "outputId": "3909cc6b-336a-4166-a383-ebafe10949fc"
      },
      "execution_count": 35,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Name    Rahul\n",
              "Age        20\n",
              "City    Delhi\n",
              "Name: 0, dtype: object"
            ],
            "text/html": [
              "<div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>0</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>Name</th>\n",
              "      <td>Rahul</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>Age</th>\n",
              "      <td>20</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>City</th>\n",
              "      <td>Delhi</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div><br><label><b>dtype:</b> object</label>"
            ]
          },
          "metadata": {},
          "execution_count": 35
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.iloc[0]"
      ],
      "metadata": {
        "id": "JYQXjFUb39wJ",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 178
        },
        "outputId": "b6b976c2-117d-49d6-86dc-94bbae1a76ff"
      },
      "execution_count": 36,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Name    Rahul\n",
              "Age        20\n",
              "City    Delhi\n",
              "Name: 0, dtype: object"
            ],
            "text/html": [
              "<div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>0</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>Name</th>\n",
              "      <td>Rahul</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>Age</th>\n",
              "      <td>20</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>City</th>\n",
              "      <td>Delhi</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div><br><label><b>dtype:</b> object</label>"
            ]
          },
          "metadata": {},
          "execution_count": 36
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.iloc[0,0]"
      ],
      "metadata": {
        "id": "aRwzifWs2S1V",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 36
        },
        "outputId": "721f812e-441e-49ca-f596-984083cddd07"
      },
      "execution_count": 37,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'Rahul'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 37
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.isnull()"
      ],
      "metadata": {
        "id": "bJzVf5Z03gO5",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 143
        },
        "outputId": "2a0d45a9-9d12-4f36-cd28-2584f40cabce"
      },
      "execution_count": 38,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "    Name    Age   City\n",
              "0  False  False  False\n",
              "1  False  False  False\n",
              "2  False  False  False"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-bda05fc6-2fb6-44bf-aea2-c52ce18f591d\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>Name</th>\n",
              "      <th>Age</th>\n",
              "      <th>City</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-bda05fc6-2fb6-44bf-aea2-c52ce18f591d')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-bda05fc6-2fb6-44bf-aea2-c52ce18f591d button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-bda05fc6-2fb6-44bf-aea2-c52ce18f591d');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 3,\n  \"fields\": [\n    {\n      \"column\": \"Name\",\n      \"properties\": {\n        \"dtype\": \"boolean\",\n        \"num_unique_values\": 1,\n        \"samples\": [\n          false\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Age\",\n      \"properties\": {\n        \"dtype\": \"boolean\",\n        \"num_unique_values\": 1,\n        \"samples\": [\n          false\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"City\",\n      \"properties\": {\n        \"dtype\": \"boolean\",\n        \"num_unique_values\": 1,\n        \"samples\": [\n          false\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 38
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.isna()"
      ],
      "metadata": {
        "id": "srR4s-qC3uOm",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 143
        },
        "outputId": "f35cc6d2-6a54-4198-e06d-db93a2fed93d"
      },
      "execution_count": 39,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "    Name    Age   City\n",
              "0  False  False  False\n",
              "1  False  False  False\n",
              "2  False  False  False"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-7ec08556-5fec-4a72-a237-555347f577b3\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>Name</th>\n",
              "      <th>Age</th>\n",
              "      <th>City</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-7ec08556-5fec-4a72-a237-555347f577b3')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-7ec08556-5fec-4a72-a237-555347f577b3 button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-7ec08556-5fec-4a72-a237-555347f577b3');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 3,\n  \"fields\": [\n    {\n      \"column\": \"Name\",\n      \"properties\": {\n        \"dtype\": \"boolean\",\n        \"num_unique_values\": 1,\n        \"samples\": [\n          false\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Age\",\n      \"properties\": {\n        \"dtype\": \"boolean\",\n        \"num_unique_values\": 1,\n        \"samples\": [\n          false\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"City\",\n      \"properties\": {\n        \"dtype\": \"boolean\",\n        \"num_unique_values\": 1,\n        \"samples\": [\n          false\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 39
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.fillna(0)"
      ],
      "metadata": {
        "id": "ydZffVce30wo",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 143
        },
        "outputId": "1de96c6e-3fbb-4fbd-fe64-569113f28dc9"
      },
      "execution_count": 40,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "    Name  Age    City\n",
              "0  Rahul   20   Delhi\n",
              "1   Aman   21  Mumbai\n",
              "2  Priya   19    Pune"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-d5839df2-cf30-4f71-aec8-963e0a85256d\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>Name</th>\n",
              "      <th>Age</th>\n",
              "      <th>City</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>Rahul</td>\n",
              "      <td>20</td>\n",
              "      <td>Delhi</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>Aman</td>\n",
              "      <td>21</td>\n",
              "      <td>Mumbai</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>Priya</td>\n",
              "      <td>19</td>\n",
              "      <td>Pune</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-d5839df2-cf30-4f71-aec8-963e0a85256d')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-d5839df2-cf30-4f71-aec8-963e0a85256d button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-d5839df2-cf30-4f71-aec8-963e0a85256d');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 3,\n  \"fields\": [\n    {\n      \"column\": \"Name\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"Rahul\",\n          \"Aman\",\n          \"Priya\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Age\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 1,\n        \"min\": 19,\n        \"max\": 21,\n        \"num_unique_values\": 3,\n        \"samples\": [\n          20,\n          21,\n          19\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"City\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"Delhi\",\n          \"Mumbai\",\n          \"Pune\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 40
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "  #what is diffrence between merge and concatenation function\n",
        "  #merge:add two columns we use this\n",
        "  # concatenate f: merge two type od datatype"
      ],
      "metadata": {
        "id": "yptnBZi84eu0"
      },
      "execution_count": 41,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "df.duplicated()"
      ],
      "metadata": {
        "id": "eQ0aPasg5PxH",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 178
        },
        "outputId": "9d2aa827-a197-4972-fb81-e22c92388e84"
      },
      "execution_count": 42,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "0    False\n",
              "1    False\n",
              "2    False\n",
              "dtype: bool"
            ],
            "text/html": [
              "<div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>0</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div><br><label><b>dtype:</b> bool</label>"
            ]
          },
          "metadata": {},
          "execution_count": 42
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "import pandas as pd\n",
        "\n",
        "# Demonstrate program for merging (matching) DataFrames\n",
        "\n",
        "df1 = pd.DataFrame({\n",
        "    'ID': [11, 22],\n",
        "    'names': ['h1', 'hello'],\n",
        "    'age': [11, 12]\n",
        "})\n",
        "\n",
        "df2 = pd.DataFrame({\n",
        "    'ID': [11, 22],\n",
        "    'city': ['hyd', 'pune'],\n",
        "    'age': [12, 13]\n",
        "})\n",
        "print(pd.merge(df1, df2, on='ID'))"
      ],
      "metadata": {
        "id": "AS9zcE6h5PXG",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "52bee43a-aa8c-4316-dcaa-65b174da9361"
      },
      "execution_count": 43,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "   ID  names  age_x  city  age_y\n",
            "0  11     h1     11   hyd     12\n",
            "1  22  hello     12  pune     13\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "pd.concat([df1,df2],axis=0)"
      ],
      "metadata": {
        "id": "Po-GZTwz66uo",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 175
        },
        "outputId": "7a29d70a-c7aa-4811-f8f8-9361b7d35f28"
      },
      "execution_count": 44,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "   ID  names  age  city\n",
              "0  11     h1   11   NaN\n",
              "1  22  hello   12   NaN\n",
              "0  11    NaN   12   hyd\n",
              "1  22    NaN   13  pune"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-16816508-d3cb-479e-a943-be9f154f8d50\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>ID</th>\n",
              "      <th>names</th>\n",
              "      <th>age</th>\n",
              "      <th>city</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>11</td>\n",
              "      <td>h1</td>\n",
              "      <td>11</td>\n",
              "      <td>NaN</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>22</td>\n",
              "      <td>hello</td>\n",
              "      <td>12</td>\n",
              "      <td>NaN</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>11</td>\n",
              "      <td>NaN</td>\n",
              "      <td>12</td>\n",
              "      <td>hyd</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>22</td>\n",
              "      <td>NaN</td>\n",
              "      <td>13</td>\n",
              "      <td>pune</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-16816508-d3cb-479e-a943-be9f154f8d50')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-16816508-d3cb-479e-a943-be9f154f8d50 button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-16816508-d3cb-479e-a943-be9f154f8d50');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "summary": "{\n  \"name\": \"pd\",\n  \"rows\": 4,\n  \"fields\": [\n    {\n      \"column\": \"ID\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 6,\n        \"min\": 11,\n        \"max\": 22,\n        \"num_unique_values\": 2,\n        \"samples\": [\n          22,\n          11\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"names\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 2,\n        \"samples\": [\n          \"hello\",\n          \"h1\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"age\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 11,\n        \"max\": 13,\n        \"num_unique_values\": 3,\n        \"samples\": [\n          11,\n          12\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"city\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 2,\n        \"samples\": [\n          \"pune\",\n          \"hyd\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 44
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "import pandas as pd\n",
        "import numpy as np\n",
        "import matplotlib.pyplot as plt\n",
        "import seaborn as sns\n",
        "\n",
        "#load dataset\n",
        "df=pd.read_csv(\"/content/Titanic-Dataset.csv\")\n",
        "df.head()"
      ],
      "metadata": {
        "id": "Syzoc6ST8Mm2",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 258
        },
        "outputId": "57183d1e-4690-4cae-be93-6de9410be8e2"
      },
      "execution_count": 253,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "   PassengerId  Survived  Pclass  \\\n",
              "0            1         0       3   \n",
              "1            2         1       1   \n",
              "2            3         1       3   \n",
              "3            4         1       1   \n",
              "4            5         0       3   \n",
              "\n",
              "                                                Name     Sex   Age  SibSp  \\\n",
              "0                            Braund, Mr. Owen Harris    male  22.0      1   \n",
              "1  Cumings, Mrs. John Bradley (Florence Briggs Th...  female  38.0      1   \n",
              "2                             Heikkinen, Miss. Laina  female  26.0      0   \n",
              "3       Futrelle, Mrs. Jacques Heath (Lily May Peel)  female  35.0      1   \n",
              "4                           Allen, Mr. William Henry    male  35.0      0   \n",
              "\n",
              "   Parch            Ticket     Fare Cabin Embarked  \n",
              "0      0         A/5 21171   7.2500   NaN        S  \n",
              "1      0          PC 17599  71.2833   C85        C  \n",
              "2      0  STON/O2. 3101282   7.9250   NaN        S  \n",
              "3      0            113803  53.1000  C123        S  \n",
              "4      0            373450   8.0500   NaN        S  "
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-ee9f68b9-e09a-4992-aaf7-a4b04a997df1\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>PassengerId</th>\n",
              "      <th>Survived</th>\n",
              "      <th>Pclass</th>\n",
              "      <th>Name</th>\n",
              "      <th>Sex</th>\n",
              "      <th>Age</th>\n",
              "      <th>SibSp</th>\n",
              "      <th>Parch</th>\n",
              "      <th>Ticket</th>\n",
              "      <th>Fare</th>\n",
              "      <th>Cabin</th>\n",
              "      <th>Embarked</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>1</td>\n",
              "      <td>0</td>\n",
              "      <td>3</td>\n",
              "      <td>Braund, Mr. Owen Harris</td>\n",
              "      <td>male</td>\n",
              "      <td>22.0</td>\n",
              "      <td>1</td>\n",
              "      <td>0</td>\n",
              "      <td>A/5 21171</td>\n",
              "      <td>7.2500</td>\n",
              "      <td>NaN</td>\n",
              "      <td>S</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>2</td>\n",
              "      <td>1</td>\n",
              "      <td>1</td>\n",
              "      <td>Cumings, Mrs. John Bradley (Florence Briggs Th...</td>\n",
              "      <td>female</td>\n",
              "      <td>38.0</td>\n",
              "      <td>1</td>\n",
              "      <td>0</td>\n",
              "      <td>PC 17599</td>\n",
              "      <td>71.2833</td>\n",
              "      <td>C85</td>\n",
              "      <td>C</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>3</td>\n",
              "      <td>1</td>\n",
              "      <td>3</td>\n",
              "      <td>Heikkinen, Miss. Laina</td>\n",
              "      <td>female</td>\n",
              "      <td>26.0</td>\n",
              "      <td>0</td>\n",
              "      <td>0</td>\n",
              "      <td>STON/O2. 3101282</td>\n",
              "      <td>7.9250</td>\n",
              "      <td>NaN</td>\n",
              "      <td>S</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>3</th>\n",
              "      <td>4</td>\n",
              "      <td>1</td>\n",
              "      <td>1</td>\n",
              "      <td>Futrelle, Mrs. Jacques Heath (Lily May Peel)</td>\n",
              "      <td>female</td>\n",
              "      <td>35.0</td>\n",
              "      <td>1</td>\n",
              "      <td>0</td>\n",
              "      <td>113803</td>\n",
              "      <td>53.1000</td>\n",
              "      <td>C123</td>\n",
              "      <td>S</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>4</th>\n",
              "      <td>5</td>\n",
              "      <td>0</td>\n",
              "      <td>3</td>\n",
              "      <td>Allen, Mr. William Henry</td>\n",
              "      <td>male</td>\n",
              "      <td>35.0</td>\n",
              "      <td>0</td>\n",
              "      <td>0</td>\n",
              "      <td>373450</td>\n",
              "      <td>8.0500</td>\n",
              "      <td>NaN</td>\n",
              "      <td>S</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-ee9f68b9-e09a-4992-aaf7-a4b04a997df1')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-ee9f68b9-e09a-4992-aaf7-a4b04a997df1 button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-ee9f68b9-e09a-4992-aaf7-a4b04a997df1');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "variable_name": "df",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 891,\n  \"fields\": [\n    {\n      \"column\": \"PassengerId\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 257,\n        \"min\": 1,\n        \"max\": 891,\n        \"num_unique_values\": 891,\n        \"samples\": [\n          710,\n          440,\n          841\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Survived\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 0,\n        \"max\": 1,\n        \"num_unique_values\": 2,\n        \"samples\": [\n          1,\n          0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Pclass\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 1,\n        \"max\": 3,\n        \"num_unique_values\": 3,\n        \"samples\": [\n          3,\n          1\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Name\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 891,\n        \"samples\": [\n          \"Moubarek, Master. Halim Gonios (\\\"William George\\\")\",\n          \"Kvillner, Mr. Johan Henrik Johannesson\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Sex\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 2,\n        \"samples\": [\n          \"female\",\n          \"male\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Age\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 14.526497332334044,\n        \"min\": 0.42,\n        \"max\": 80.0,\n        \"num_unique_values\": 88,\n        \"samples\": [\n          0.75,\n          22.0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"SibSp\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 1,\n        \"min\": 0,\n        \"max\": 8,\n        \"num_unique_values\": 7,\n        \"samples\": [\n          1,\n          0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Parch\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 0,\n        \"max\": 6,\n        \"num_unique_values\": 7,\n        \"samples\": [\n          0,\n          1\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Ticket\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 681,\n        \"samples\": [\n          \"11774\",\n          \"248740\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Fare\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 49.693428597180905,\n        \"min\": 0.0,\n        \"max\": 512.3292,\n        \"num_unique_values\": 248,\n        \"samples\": [\n          11.2417,\n          51.8625\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Cabin\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 147,\n        \"samples\": [\n          \"D45\",\n          \"B49\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Embarked\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"S\",\n          \"C\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 253
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Data Cleaning is a process of identifying and correcting inacurate, inconsitant, duplicate and incomplete data before analysis and model building.\n",
        "\n",
        "# Why Data Cleaning is important\n",
        "#  It improves Dat Quality\n",
        "# It increases model accuracy.\n",
        "# It removes errors\n",
        "# It reduces Noise\n",
        "# It saves Preceesing Time"
      ],
      "metadata": {
        "id": "YHxDoAbEB6qO"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "df.columns"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "6P-QPuGYB7in",
        "outputId": "062eaabe-7193-487a-fe74-ae490b3420dc"
      },
      "execution_count": 46,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Index(['Name', 'Age', 'City'], dtype='object')"
            ]
          },
          "metadata": {},
          "execution_count": 46
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.duplicated().sum()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "EBw9VobPF0oI",
        "outputId": "d4ada093-9517-4118-af2a-d8d925c54b89"
      },
      "execution_count": 47,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "np.int64(0)"
            ]
          },
          "metadata": {},
          "execution_count": 47
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.drop_duplicates(inplace=True)"
      ],
      "metadata": {
        "id": "pd0eFO53F2W2"
      },
      "execution_count": 48,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "df.rename(columns={'Pclass': 'PassengerClass'}, inplace=True)"
      ],
      "metadata": {
        "id": "p0nWlBDDF3-7"
      },
      "execution_count": 49,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [],
      "metadata": {
        "id": "hPWMNYmOF51w"
      },
      "execution_count": 49,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Day 5 (Matplotlib)"
      ],
      "metadata": {
        "id": "f5ahzEOu6LrB"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "# EDA(Explorataty data analysis) is the process of understanding data using statistic and visulization before building machine learning models"
      ],
      "metadata": {
        "id": "xAQ15spy7Ba4"
      },
      "execution_count": 240,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "import numpy as np\n",
        "import pandas as pd\n",
        "import matplotlib.pyplot as plt\n",
        "import seaborn as sns\n",
        "\n",
        "df = pd.read_csv(\"/content/Titanic-Dataset.csv\")\n",
        "df.head()"
      ],
      "metadata": {
        "id": "OXmxcQge9Fk_",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 258
        },
        "outputId": "2f4a0cf4-c24b-4e29-eff3-b961c11db236"
      },
      "execution_count": 243,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "   PassengerId  Survived  Pclass  \\\n",
              "0            1         0       3   \n",
              "1            2         1       1   \n",
              "2            3         1       3   \n",
              "3            4         1       1   \n",
              "4            5         0       3   \n",
              "\n",
              "                                                Name     Sex   Age  SibSp  \\\n",
              "0                            Braund, Mr. Owen Harris    male  22.0      1   \n",
              "1  Cumings, Mrs. John Bradley (Florence Briggs Th...  female  38.0      1   \n",
              "2                             Heikkinen, Miss. Laina  female  26.0      0   \n",
              "3       Futrelle, Mrs. Jacques Heath (Lily May Peel)  female  35.0      1   \n",
              "4                           Allen, Mr. William Henry    male  35.0      0   \n",
              "\n",
              "   Parch            Ticket     Fare Cabin Embarked  \n",
              "0      0         A/5 21171   7.2500   NaN        S  \n",
              "1      0          PC 17599  71.2833   C85        C  \n",
              "2      0  STON/O2. 3101282   7.9250   NaN        S  \n",
              "3      0            113803  53.1000  C123        S  \n",
              "4      0            373450   8.0500   NaN        S  "
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-d8fb1927-3fdc-4346-9535-25d58fc73e48\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>PassengerId</th>\n",
              "      <th>Survived</th>\n",
              "      <th>Pclass</th>\n",
              "      <th>Name</th>\n",
              "      <th>Sex</th>\n",
              "      <th>Age</th>\n",
              "      <th>SibSp</th>\n",
              "      <th>Parch</th>\n",
              "      <th>Ticket</th>\n",
              "      <th>Fare</th>\n",
              "      <th>Cabin</th>\n",
              "      <th>Embarked</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>1</td>\n",
              "      <td>0</td>\n",
              "      <td>3</td>\n",
              "      <td>Braund, Mr. Owen Harris</td>\n",
              "      <td>male</td>\n",
              "      <td>22.0</td>\n",
              "      <td>1</td>\n",
              "      <td>0</td>\n",
              "      <td>A/5 21171</td>\n",
              "      <td>7.2500</td>\n",
              "      <td>NaN</td>\n",
              "      <td>S</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>2</td>\n",
              "      <td>1</td>\n",
              "      <td>1</td>\n",
              "      <td>Cumings, Mrs. John Bradley (Florence Briggs Th...</td>\n",
              "      <td>female</td>\n",
              "      <td>38.0</td>\n",
              "      <td>1</td>\n",
              "      <td>0</td>\n",
              "      <td>PC 17599</td>\n",
              "      <td>71.2833</td>\n",
              "      <td>C85</td>\n",
              "      <td>C</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>3</td>\n",
              "      <td>1</td>\n",
              "      <td>3</td>\n",
              "      <td>Heikkinen, Miss. Laina</td>\n",
              "      <td>female</td>\n",
              "      <td>26.0</td>\n",
              "      <td>0</td>\n",
              "      <td>0</td>\n",
              "      <td>STON/O2. 3101282</td>\n",
              "      <td>7.9250</td>\n",
              "      <td>NaN</td>\n",
              "      <td>S</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>3</th>\n",
              "      <td>4</td>\n",
              "      <td>1</td>\n",
              "      <td>1</td>\n",
              "      <td>Futrelle, Mrs. Jacques Heath (Lily May Peel)</td>\n",
              "      <td>female</td>\n",
              "      <td>35.0</td>\n",
              "      <td>1</td>\n",
              "      <td>0</td>\n",
              "      <td>113803</td>\n",
              "      <td>53.1000</td>\n",
              "      <td>C123</td>\n",
              "      <td>S</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>4</th>\n",
              "      <td>5</td>\n",
              "      <td>0</td>\n",
              "      <td>3</td>\n",
              "      <td>Allen, Mr. William Henry</td>\n",
              "      <td>male</td>\n",
              "      <td>35.0</td>\n",
              "      <td>0</td>\n",
              "      <td>0</td>\n",
              "      <td>373450</td>\n",
              "      <td>8.0500</td>\n",
              "      <td>NaN</td>\n",
              "      <td>S</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-d8fb1927-3fdc-4346-9535-25d58fc73e48')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-d8fb1927-3fdc-4346-9535-25d58fc73e48 button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-d8fb1927-3fdc-4346-9535-25d58fc73e48');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "variable_name": "df",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 891,\n  \"fields\": [\n    {\n      \"column\": \"PassengerId\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 257,\n        \"min\": 1,\n        \"max\": 891,\n        \"num_unique_values\": 891,\n        \"samples\": [\n          710,\n          440,\n          841\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Survived\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 0,\n        \"max\": 1,\n        \"num_unique_values\": 2,\n        \"samples\": [\n          1,\n          0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Pclass\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 1,\n        \"max\": 3,\n        \"num_unique_values\": 3,\n        \"samples\": [\n          3,\n          1\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Name\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 891,\n        \"samples\": [\n          \"Moubarek, Master. Halim Gonios (\\\"William George\\\")\",\n          \"Kvillner, Mr. Johan Henrik Johannesson\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Sex\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 2,\n        \"samples\": [\n          \"female\",\n          \"male\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Age\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 14.526497332334044,\n        \"min\": 0.42,\n        \"max\": 80.0,\n        \"num_unique_values\": 88,\n        \"samples\": [\n          0.75,\n          22.0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"SibSp\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 1,\n        \"min\": 0,\n        \"max\": 8,\n        \"num_unique_values\": 7,\n        \"samples\": [\n          1,\n          0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Parch\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 0,\n        \"max\": 6,\n        \"num_unique_values\": 7,\n        \"samples\": [\n          0,\n          1\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Ticket\",\n      \"properties\": {\n        \"dtype\": \"string\",\n        \"num_unique_values\": 681,\n        \"samples\": [\n          \"11774\",\n          \"248740\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Fare\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 49.693428597180905,\n        \"min\": 0.0,\n        \"max\": 512.3292,\n        \"num_unique_values\": 248,\n        \"samples\": [\n          11.2417,\n          51.8625\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Cabin\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 147,\n        \"samples\": [\n          \"D45\",\n          \"B49\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Embarked\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"S\",\n          \"C\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 243
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.describe()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 300
        },
        "id": "jOznIbpOAwUY",
        "outputId": "8ce43741-0de1-456d-d22e-62d05568e4e6"
      },
      "execution_count": 244,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "       PassengerId    Survived      Pclass         Age       SibSp  \\\n",
              "count   891.000000  891.000000  891.000000  714.000000  891.000000   \n",
              "mean    446.000000    0.383838    2.308642   29.699118    0.523008   \n",
              "std     257.353842    0.486592    0.836071   14.526497    1.102743   \n",
              "min       1.000000    0.000000    1.000000    0.420000    0.000000   \n",
              "25%     223.500000    0.000000    2.000000   20.125000    0.000000   \n",
              "50%     446.000000    0.000000    3.000000   28.000000    0.000000   \n",
              "75%     668.500000    1.000000    3.000000   38.000000    1.000000   \n",
              "max     891.000000    1.000000    3.000000   80.000000    8.000000   \n",
              "\n",
              "            Parch        Fare  \n",
              "count  891.000000  891.000000  \n",
              "mean     0.381594   32.204208  \n",
              "std      0.806057   49.693429  \n",
              "min      0.000000    0.000000  \n",
              "25%      0.000000    7.910400  \n",
              "50%      0.000000   14.454200  \n",
              "75%      0.000000   31.000000  \n",
              "max      6.000000  512.329200  "
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-5060c0df-16cc-4d5d-a06c-8f6cc645427f\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>PassengerId</th>\n",
              "      <th>Survived</th>\n",
              "      <th>Pclass</th>\n",
              "      <th>Age</th>\n",
              "      <th>SibSp</th>\n",
              "      <th>Parch</th>\n",
              "      <th>Fare</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>count</th>\n",
              "      <td>891.000000</td>\n",
              "      <td>891.000000</td>\n",
              "      <td>891.000000</td>\n",
              "      <td>714.000000</td>\n",
              "      <td>891.000000</td>\n",
              "      <td>891.000000</td>\n",
              "      <td>891.000000</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>mean</th>\n",
              "      <td>446.000000</td>\n",
              "      <td>0.383838</td>\n",
              "      <td>2.308642</td>\n",
              "      <td>29.699118</td>\n",
              "      <td>0.523008</td>\n",
              "      <td>0.381594</td>\n",
              "      <td>32.204208</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>std</th>\n",
              "      <td>257.353842</td>\n",
              "      <td>0.486592</td>\n",
              "      <td>0.836071</td>\n",
              "      <td>14.526497</td>\n",
              "      <td>1.102743</td>\n",
              "      <td>0.806057</td>\n",
              "      <td>49.693429</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>min</th>\n",
              "      <td>1.000000</td>\n",
              "      <td>0.000000</td>\n",
              "      <td>1.000000</td>\n",
              "      <td>0.420000</td>\n",
              "      <td>0.000000</td>\n",
              "      <td>0.000000</td>\n",
              "      <td>0.000000</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>25%</th>\n",
              "      <td>223.500000</td>\n",
              "      <td>0.000000</td>\n",
              "      <td>2.000000</td>\n",
              "      <td>20.125000</td>\n",
              "      <td>0.000000</td>\n",
              "      <td>0.000000</td>\n",
              "      <td>7.910400</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>50%</th>\n",
              "      <td>446.000000</td>\n",
              "      <td>0.000000</td>\n",
              "      <td>3.000000</td>\n",
              "      <td>28.000000</td>\n",
              "      <td>0.000000</td>\n",
              "      <td>0.000000</td>\n",
              "      <td>14.454200</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>75%</th>\n",
              "      <td>668.500000</td>\n",
              "      <td>1.000000</td>\n",
              "      <td>3.000000</td>\n",
              "      <td>38.000000</td>\n",
              "      <td>1.000000</td>\n",
              "      <td>0.000000</td>\n",
              "      <td>31.000000</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>max</th>\n",
              "      <td>891.000000</td>\n",
              "      <td>1.000000</td>\n",
              "      <td>3.000000</td>\n",
              "      <td>80.000000</td>\n",
              "      <td>8.000000</td>\n",
              "      <td>6.000000</td>\n",
              "      <td>512.329200</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-5060c0df-16cc-4d5d-a06c-8f6cc645427f')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-5060c0df-16cc-4d5d-a06c-8f6cc645427f button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-5060c0df-16cc-4d5d-a06c-8f6cc645427f');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 8,\n  \"fields\": [\n    {\n      \"column\": \"PassengerId\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 320.8159711429856,\n        \"min\": 1.0,\n        \"max\": 891.0,\n        \"num_unique_values\": 6,\n        \"samples\": [\n          891.0,\n          446.0,\n          668.5\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Survived\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 314.8713661874558,\n        \"min\": 0.0,\n        \"max\": 891.0,\n        \"num_unique_values\": 5,\n        \"samples\": [\n          0.3838383838383838,\n          1.0,\n          0.4865924542648585\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Pclass\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 314.2523437079693,\n        \"min\": 0.8360712409770513,\n        \"max\": 891.0,\n        \"num_unique_values\": 6,\n        \"samples\": [\n          891.0,\n          2.308641975308642,\n          3.0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Age\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 242.9056731818781,\n        \"min\": 0.42,\n        \"max\": 714.0,\n        \"num_unique_values\": 8,\n        \"samples\": [\n          29.69911764705882,\n          28.0,\n          714.0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"SibSp\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 314.4908277465442,\n        \"min\": 0.0,\n        \"max\": 891.0,\n        \"num_unique_values\": 6,\n        \"samples\": [\n          891.0,\n          0.5230078563411896,\n          8.0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Parch\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 314.65971717879,\n        \"min\": 0.0,\n        \"max\": 891.0,\n        \"num_unique_values\": 5,\n        \"samples\": [\n          0.38159371492704824,\n          6.0,\n          0.8060572211299559\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Fare\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 330.6256632228577,\n        \"min\": 0.0,\n        \"max\": 891.0,\n        \"num_unique_values\": 8,\n        \"samples\": [\n          32.204207968574636,\n          14.4542,\n          891.0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 244
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(df.isnull().sum()/len(df))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "KyN66yaKAz26",
        "outputId": "e0caefd4-6b27-4e7d-f370-85583f2dbdbf"
      },
      "execution_count": 248,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "PassengerId    0.000000\n",
            "Survived       0.000000\n",
            "Pclass         0.000000\n",
            "Name           0.000000\n",
            "Sex            0.000000\n",
            "Age            0.198653\n",
            "SibSp          0.000000\n",
            "Parch          0.000000\n",
            "Ticket         0.000000\n",
            "Fare           0.000000\n",
            "Cabin          0.771044\n",
            "Embarked       0.002245\n",
            "dtype: float64\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#fill missing values in age using\n",
        "df['Age']=df['Age'].fillna(df['Age'].mean())\n"
      ],
      "metadata": {
        "id": "dSsnwSOWDXku"
      },
      "execution_count": 249,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "print(df['Age'].isnull().sum())"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "YsmVdGjwDnL6",
        "outputId": "15ded016-105c-4ce4-d55a-aef15aa1988d"
      },
      "execution_count": 250,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.duplicated().sum()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "nSbByhrOD8Hp",
        "outputId": "2ecfe994-bb24-48a7-9806-9193008ab72f"
      },
      "execution_count": 251,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "np.int64(0)"
            ]
          },
          "metadata": {},
          "execution_count": 251
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "plt.figure(figsize=(3,5))\n",
        "sns.boxplot(x=df['Age'])\n",
        "plt.title(\"box plot of Age\")\n",
        "plt.show()"
      ],
      "metadata": {
        "id": "BnbvowTLEAt4",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 487
        },
        "outputId": "aeed8c5b-ea9c-47ea-b55c-18ecd69102b7"
      },
      "execution_count": 252,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 300x500 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Day 6"
      ],
      "metadata": {
        "id": "shsUsHocFs5S"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "# AI\n",
        "#Ai is the broad field which mimics human intellegence\n",
        "# its is machine  which automates the human task a\n",
        "\n",
        "\n",
        "#Types of AI\n",
        "# Narrow AI : alexa / siri-++q# EDGE AI/:   IOT + ALEXA ,SIRI . eg : tesla\n",
        "# Gen AI :    chatgpt,gemni,cluade\n",
        "# Agentic AI\n",
        "# Robotic AI\n",
        "# Personal AI"
      ],
      "metadata": {
        "id": "SgmDIa5iFLuV"
      },
      "execution_count": 58,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": [
        "###DAY 7 (LinearRegression)"
      ],
      "metadata": {
        "id": "7DmmvYItNdGJ"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "# write a program in python to print the memory occupied by python list and numpy array?.\n",
        "import sys\n",
        "import numpy as np\n",
        "\n",
        "list=[1,2,3,4,5]\n",
        "arr=np.array([1,2,3,4,5])\n",
        "\n",
        "print(sys.getsizeof(list))\n",
        "print(arr.nbytes)\n",
        "\n",
        "# numpy array is faster than python list."
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "yclbBmT4NftP",
        "outputId": "d7058eb8-bcd0-4011-c6d9-2fbffb31d4a0"
      },
      "execution_count": 59,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "104\n",
            "40\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#ML\n",
        "\n",
        "#Machine learning is a subset of AI which is used to train the machine based upon the past data,\n",
        "#the machine learns pattern  from the historical data based upon that it predicts the output.\n",
        "\n",
        "# types of machine leaning\n",
        "# 1. Supervised\n",
        "# 2. Unsupervised\n",
        "# 3. Reinforcement\n",
        "\n",
        "    #Linear Regression\n",
        "    #Linea regression is supervised machine learning algorithm using to predict continueous numerical\n",
        "    #value by establishing linear relationship between indepented variables (features) and\n",
        "    #the dependent variable whioch is target.\n",
        "    # Eg:hoiuse price prediction,sales prediction etc.\n",
        "    # y=mx+c\n",
        "    # y= B0 + B1x1+B2x2+...Bnxn where B is target variable x is the input feature B0 is intersept which is (bias) in B1 to B2 is know as coffecient which is know as weight\n",
        "    # work flow of linear regression\n",
        "    #model training :model training means teaching the model using hiostorical data so he can learn patterns\n",
        "\n"
      ],
      "metadata": {
        "id": "uDtaAGsCOm9a"
      },
      "execution_count": 281,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "# step 1: import libraries\n",
        "import numpy as np\n",
        "import pandas as pd\n",
        "\n",
        "from sklearn.model_selection import train_test_split\n",
        "from sklearn.linear_model import LinearRegression\n",
        "from sklearn.metrics import mean_squared_error, r2_score, mean_absolute_error\n",
        "from sklearn.preprocessing import OneHotEncoder, LabelEncoder, MinMaxScaler, StandardScaler\n",
        "from sklearn.compose import make_column_transformer\n",
        "from sklearn.pipeline import make_pipeline\n",
        "from sklearn.compose import ColumnTransformer\n",
        "from sklearn.pipeline import Pipeline"
      ],
      "metadata": {
        "id": "G8RXumairJiZ"
      },
      "execution_count": 282,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "#step 2:load dataset\n",
        "df=pd.read_csv(\"/content/house-prices.csv\")"
      ],
      "metadata": {
        "id": "Rx_MJVM7Xfom"
      },
      "execution_count": 153,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "df.head()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 206
        },
        "id": "uQpWJNL7fYaG",
        "outputId": "ee36117c-bff5-4eed-ee8a-359bb58bd4dd"
      },
      "execution_count": 154,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "   Home   Price  SqFt  Bedrooms  Bathrooms  Offers Brick Neighborhood\n",
              "0     1  114300  1790         2          2       2    No         East\n",
              "1     2  114200  2030         4          2       3    No         East\n",
              "2     3  114800  1740         3          2       1    No         East\n",
              "3     4   94700  1980         3          2       3    No         East\n",
              "4     5  119800  2130         3          3       3    No         East"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-1183cbb0-a3b3-40da-a7bd-b7d573405e9a\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>Home</th>\n",
              "      <th>Price</th>\n",
              "      <th>SqFt</th>\n",
              "      <th>Bedrooms</th>\n",
              "      <th>Bathrooms</th>\n",
              "      <th>Offers</th>\n",
              "      <th>Brick</th>\n",
              "      <th>Neighborhood</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>1</td>\n",
              "      <td>114300</td>\n",
              "      <td>1790</td>\n",
              "      <td>2</td>\n",
              "      <td>2</td>\n",
              "      <td>2</td>\n",
              "      <td>No</td>\n",
              "      <td>East</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>2</td>\n",
              "      <td>114200</td>\n",
              "      <td>2030</td>\n",
              "      <td>4</td>\n",
              "      <td>2</td>\n",
              "      <td>3</td>\n",
              "      <td>No</td>\n",
              "      <td>East</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>3</td>\n",
              "      <td>114800</td>\n",
              "      <td>1740</td>\n",
              "      <td>3</td>\n",
              "      <td>2</td>\n",
              "      <td>1</td>\n",
              "      <td>No</td>\n",
              "      <td>East</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>3</th>\n",
              "      <td>4</td>\n",
              "      <td>94700</td>\n",
              "      <td>1980</td>\n",
              "      <td>3</td>\n",
              "      <td>2</td>\n",
              "      <td>3</td>\n",
              "      <td>No</td>\n",
              "      <td>East</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>4</th>\n",
              "      <td>5</td>\n",
              "      <td>119800</td>\n",
              "      <td>2130</td>\n",
              "      <td>3</td>\n",
              "      <td>3</td>\n",
              "      <td>3</td>\n",
              "      <td>No</td>\n",
              "      <td>East</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-1183cbb0-a3b3-40da-a7bd-b7d573405e9a')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-1183cbb0-a3b3-40da-a7bd-b7d573405e9a button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-1183cbb0-a3b3-40da-a7bd-b7d573405e9a');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "variable_name": "df",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 128,\n  \"fields\": [\n    {\n      \"column\": \"Home\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 37,\n        \"min\": 1,\n        \"max\": 128,\n        \"num_unique_values\": 128,\n        \"samples\": [\n          56,\n          41,\n          20\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Price\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 26868,\n        \"min\": 69100,\n        \"max\": 211200,\n        \"num_unique_values\": 123,\n        \"samples\": [\n          111400,\n          103200,\n          90300\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"SqFt\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 211,\n        \"min\": 1450,\n        \"max\": 2590,\n        \"num_unique_values\": 61,\n        \"samples\": [\n          1790,\n          1780,\n          2140\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Bedrooms\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 2,\n        \"max\": 5,\n        \"num_unique_values\": 4,\n        \"samples\": [\n          4,\n          5,\n          2\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Bathrooms\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 2,\n        \"max\": 4,\n        \"num_unique_values\": 3,\n        \"samples\": [\n          2,\n          3,\n          4\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Offers\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 1,\n        \"min\": 1,\n        \"max\": 6,\n        \"num_unique_values\": 6,\n        \"samples\": [\n          2,\n          3,\n          6\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Brick\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 2,\n        \"samples\": [\n          \"Yes\",\n          \"No\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Neighborhood\",\n      \"properties\": {\n        \"dtype\": \"category\",\n        \"num_unique_values\": 3,\n        \"samples\": [\n          \"East\",\n          \"North\"\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 154
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#seprate feature and target\n",
        "X=df[['SqFt', 'Bathrooms', 'Bedrooms', 'Offers', 'Brick', 'Neighborhood']]\n",
        "y=df['Price']"
      ],
      "metadata": {
        "id": "L8pNYRAefZzC"
      },
      "execution_count": 168,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "df.info()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "9sXLdFRYgJYq",
        "outputId": "1d682692-a3ea-44dc-9bee-ca0101df6b7a"
      },
      "execution_count": 156,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'pandas.core.frame.DataFrame'>\n",
            "RangeIndex: 128 entries, 0 to 127\n",
            "Data columns (total 8 columns):\n",
            " #   Column        Non-Null Count  Dtype \n",
            "---  ------        --------------  ----- \n",
            " 0   Home          128 non-null    int64 \n",
            " 1   Price         128 non-null    int64 \n",
            " 2   SqFt          128 non-null    int64 \n",
            " 3   Bedrooms      128 non-null    int64 \n",
            " 4   Bathrooms     128 non-null    int64 \n",
            " 5   Offers        128 non-null    int64 \n",
            " 6   Brick         128 non-null    object\n",
            " 7   Neighborhood  128 non-null    object\n",
            "dtypes: int64(6), object(2)\n",
            "memory usage: 8.1+ KB\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.columns"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "rDWEvXOggjUL",
        "outputId": "3fbe61f6-969e-431e-c9d5-aa731f05620b"
      },
      "execution_count": 157,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Index(['Home', 'Price', 'SqFt', 'Bedrooms', 'Bathrooms', 'Offers', 'Brick',\n",
              "       'Neighborhood'],\n",
              "      dtype='object')"
            ]
          },
          "metadata": {},
          "execution_count": 157
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "x=df.drop(columns=['Brick',\"Neighborhood\"],axis=1)\n",
        "y = df['Price']"
      ],
      "metadata": {
        "id": "RVs0BbXMg7N2"
      },
      "execution_count": 170,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "categorical_columns = ['Brick', 'Neighborhood']\n",
        "numerical_columns = ['SqFt', 'Bathrooms', 'Bedrooms', 'Offers']"
      ],
      "metadata": {
        "id": "E4jISy_2h2Rx"
      },
      "execution_count": 171,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "preprocessor=ColumnTransformer(transformers=[\n",
        "    ('scaling',MinMaxScaler(),numerical_columns),\n",
        "    ('onehot',OneHotEncoder(),categorical_columns)\n",
        "])"
      ],
      "metadata": {
        "id": "Xxua5F6jiU9v"
      },
      "execution_count": 183,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "X_train,X_test,y_train,y_test=train_test_split(X,y,test_size=0.2,random_state=42)"
      ],
      "metadata": {
        "id": "h6WVO1OCqq2d"
      },
      "execution_count": 195,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "model = Pipeline([\n",
        "    ('preprocessor', preprocessor),\n",
        "    ('regressor', LinearRegression())\n",
        "])"
      ],
      "metadata": {
        "id": "om9xefTLq5R-"
      },
      "execution_count": 196,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "model.fit(X_train,y_train)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 246
        },
        "id": "dCYEN0DKtb_f",
        "outputId": "ce1074a6-9541-462c-8b2c-59cd02153a88"
      },
      "execution_count": 197,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Pipeline(steps=[('preprocessor',\n",
              "                 ColumnTransformer(transformers=[('scaling', MinMaxScaler(),\n",
              "                                                  ['SqFt', 'Bathrooms',\n",
              "                                                   'Bedrooms', 'Offers']),\n",
              "                                                 ('onehot', OneHotEncoder(),\n",
              "                                                  ['Brick', 'Neighborhood'])])),\n",
              "                ('regressor', LinearRegression())])"
            ],
            "text/html": [
              "<style>#sk-container-id-7 {\n",
              "  /* Definition of color scheme common for light and dark mode */\n",
              "  --sklearn-color-text: #000;\n",
              "  --sklearn-color-text-muted: #666;\n",
              "  --sklearn-color-line: gray;\n",
              "  /* Definition of color scheme for unfitted estimators */\n",
              "  --sklearn-color-unfitted-level-0: #fff5e6;\n",
              "  --sklearn-color-unfitted-level-1: #f6e4d2;\n",
              "  --sklearn-color-unfitted-level-2: #ffe0b3;\n",
              "  --sklearn-color-unfitted-level-3: chocolate;\n",
              "  /* Definition of color scheme for fitted estimators */\n",
              "  --sklearn-color-fitted-level-0: #f0f8ff;\n",
              "  --sklearn-color-fitted-level-1: #d4ebff;\n",
              "  --sklearn-color-fitted-level-2: #b3dbfd;\n",
              "  --sklearn-color-fitted-level-3: cornflowerblue;\n",
              "\n",
              "  /* Specific color for light theme */\n",
              "  --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));\n",
              "  --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, white)));\n",
              "  --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));\n",
              "  --sklearn-color-icon: #696969;\n",
              "\n",
              "  @media (prefers-color-scheme: dark) {\n",
              "    /* Redefinition of color scheme for dark theme */\n",
              "    --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));\n",
              "    --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, #111)));\n",
              "    --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));\n",
              "    --sklearn-color-icon: #878787;\n",
              "  }\n",
              "}\n",
              "\n",
              "#sk-container-id-7 {\n",
              "  color: var(--sklearn-color-text);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 pre {\n",
              "  padding: 0;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 input.sk-hidden--visually {\n",
              "  border: 0;\n",
              "  clip: rect(1px 1px 1px 1px);\n",
              "  clip: rect(1px, 1px, 1px, 1px);\n",
              "  height: 1px;\n",
              "  margin: -1px;\n",
              "  overflow: hidden;\n",
              "  padding: 0;\n",
              "  position: absolute;\n",
              "  width: 1px;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-dashed-wrapped {\n",
              "  border: 1px dashed var(--sklearn-color-line);\n",
              "  margin: 0 0.4em 0.5em 0.4em;\n",
              "  box-sizing: border-box;\n",
              "  padding-bottom: 0.4em;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-container {\n",
              "  /* jupyter's `normalize.less` sets `[hidden] { display: none; }`\n",
              "     but bootstrap.min.css set `[hidden] { display: none !important; }`\n",
              "     so we also need the `!important` here to be able to override the\n",
              "     default hidden behavior on the sphinx rendered scikit-learn.org.\n",
              "     See: https://github.com/scikit-learn/scikit-learn/issues/21755 */\n",
              "  display: inline-block !important;\n",
              "  position: relative;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-text-repr-fallback {\n",
              "  display: none;\n",
              "}\n",
              "\n",
              "div.sk-parallel-item,\n",
              "div.sk-serial,\n",
              "div.sk-item {\n",
              "  /* draw centered vertical line to link estimators */\n",
              "  background-image: linear-gradient(var(--sklearn-color-text-on-default-background), var(--sklearn-color-text-on-default-background));\n",
              "  background-size: 2px 100%;\n",
              "  background-repeat: no-repeat;\n",
              "  background-position: center center;\n",
              "}\n",
              "\n",
              "/* Parallel-specific style estimator block */\n",
              "\n",
              "#sk-container-id-7 div.sk-parallel-item::after {\n",
              "  content: \"\";\n",
              "  width: 100%;\n",
              "  border-bottom: 2px solid var(--sklearn-color-text-on-default-background);\n",
              "  flex-grow: 1;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-parallel {\n",
              "  display: flex;\n",
              "  align-items: stretch;\n",
              "  justify-content: center;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  position: relative;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-parallel-item {\n",
              "  display: flex;\n",
              "  flex-direction: column;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-parallel-item:first-child::after {\n",
              "  align-self: flex-end;\n",
              "  width: 50%;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-parallel-item:last-child::after {\n",
              "  align-self: flex-start;\n",
              "  width: 50%;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-parallel-item:only-child::after {\n",
              "  width: 0;\n",
              "}\n",
              "\n",
              "/* Serial-specific style estimator block */\n",
              "\n",
              "#sk-container-id-7 div.sk-serial {\n",
              "  display: flex;\n",
              "  flex-direction: column;\n",
              "  align-items: center;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  padding-right: 1em;\n",
              "  padding-left: 1em;\n",
              "}\n",
              "\n",
              "\n",
              "/* Toggleable style: style used for estimator/Pipeline/ColumnTransformer box that is\n",
              "clickable and can be expanded/collapsed.\n",
              "- Pipeline and ColumnTransformer use this feature and define the default style\n",
              "- Estimators will overwrite some part of the style using the `sk-estimator` class\n",
              "*/\n",
              "\n",
              "/* Pipeline and ColumnTransformer style (default) */\n",
              "\n",
              "#sk-container-id-7 div.sk-toggleable {\n",
              "  /* Default theme specific background. It is overwritten whether we have a\n",
              "  specific estimator or a Pipeline/ColumnTransformer */\n",
              "  background-color: var(--sklearn-color-background);\n",
              "}\n",
              "\n",
              "/* Toggleable label */\n",
              "#sk-container-id-7 label.sk-toggleable__label {\n",
              "  cursor: pointer;\n",
              "  display: flex;\n",
              "  width: 100%;\n",
              "  margin-bottom: 0;\n",
              "  padding: 0.5em;\n",
              "  box-sizing: border-box;\n",
              "  text-align: center;\n",
              "  align-items: start;\n",
              "  justify-content: space-between;\n",
              "  gap: 0.5em;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 label.sk-toggleable__label .caption {\n",
              "  font-size: 0.6rem;\n",
              "  font-weight: lighter;\n",
              "  color: var(--sklearn-color-text-muted);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 label.sk-toggleable__label-arrow:before {\n",
              "  /* Arrow on the left of the label */\n",
              "  content: \"▸\";\n",
              "  float: left;\n",
              "  margin-right: 0.25em;\n",
              "  color: var(--sklearn-color-icon);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 label.sk-toggleable__label-arrow:hover:before {\n",
              "  color: var(--sklearn-color-text);\n",
              "}\n",
              "\n",
              "/* Toggleable content - dropdown */\n",
              "\n",
              "#sk-container-id-7 div.sk-toggleable__content {\n",
              "  max-height: 0;\n",
              "  max-width: 0;\n",
              "  overflow: hidden;\n",
              "  text-align: left;\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-toggleable__content.fitted {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-toggleable__content pre {\n",
              "  margin: 0.2em;\n",
              "  border-radius: 0.25em;\n",
              "  color: var(--sklearn-color-text);\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-toggleable__content.fitted pre {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 input.sk-toggleable__control:checked~div.sk-toggleable__content {\n",
              "  /* Expand drop-down */\n",
              "  max-height: 200px;\n",
              "  max-width: 100%;\n",
              "  overflow: auto;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 input.sk-toggleable__control:checked~label.sk-toggleable__label-arrow:before {\n",
              "  content: \"▾\";\n",
              "}\n",
              "\n",
              "/* Pipeline/ColumnTransformer-specific style */\n",
              "\n",
              "#sk-container-id-7 div.sk-label input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-label.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Estimator-specific style */\n",
              "\n",
              "/* Colorize estimator box */\n",
              "#sk-container-id-7 div.sk-estimator input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-estimator.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-label label.sk-toggleable__label,\n",
              "#sk-container-id-7 div.sk-label label {\n",
              "  /* The background is the default theme color */\n",
              "  color: var(--sklearn-color-text-on-default-background);\n",
              "}\n",
              "\n",
              "/* On hover, darken the color of the background */\n",
              "#sk-container-id-7 div.sk-label:hover label.sk-toggleable__label {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "/* Label box, darken color on hover, fitted */\n",
              "#sk-container-id-7 div.sk-label.fitted:hover label.sk-toggleable__label.fitted {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Estimator label */\n",
              "\n",
              "#sk-container-id-7 div.sk-label label {\n",
              "  font-family: monospace;\n",
              "  font-weight: bold;\n",
              "  display: inline-block;\n",
              "  line-height: 1.2em;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-label-container {\n",
              "  text-align: center;\n",
              "}\n",
              "\n",
              "/* Estimator-specific */\n",
              "#sk-container-id-7 div.sk-estimator {\n",
              "  font-family: monospace;\n",
              "  border: 1px dotted var(--sklearn-color-border-box);\n",
              "  border-radius: 0.25em;\n",
              "  box-sizing: border-box;\n",
              "  margin-bottom: 0.5em;\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-estimator.fitted {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "/* on hover */\n",
              "#sk-container-id-7 div.sk-estimator:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-7 div.sk-estimator.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Specification for estimator info (e.g. \"i\" and \"?\") */\n",
              "\n",
              "/* Common style for \"i\" and \"?\" */\n",
              "\n",
              ".sk-estimator-doc-link,\n",
              "a:link.sk-estimator-doc-link,\n",
              "a:visited.sk-estimator-doc-link {\n",
              "  float: right;\n",
              "  font-size: smaller;\n",
              "  line-height: 1em;\n",
              "  font-family: monospace;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  border-radius: 1em;\n",
              "  height: 1em;\n",
              "  width: 1em;\n",
              "  text-decoration: none !important;\n",
              "  margin-left: 0.5em;\n",
              "  text-align: center;\n",
              "  /* unfitted */\n",
              "  border: var(--sklearn-color-unfitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-unfitted-level-1);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link.fitted,\n",
              "a:link.sk-estimator-doc-link.fitted,\n",
              "a:visited.sk-estimator-doc-link.fitted {\n",
              "  /* fitted */\n",
              "  border: var(--sklearn-color-fitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-fitted-level-1);\n",
              "}\n",
              "\n",
              "/* On hover */\n",
              "div.sk-estimator:hover .sk-estimator-doc-link:hover,\n",
              ".sk-estimator-doc-link:hover,\n",
              "div.sk-label-container:hover .sk-estimator-doc-link:hover,\n",
              ".sk-estimator-doc-link:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "div.sk-estimator.fitted:hover .sk-estimator-doc-link.fitted:hover,\n",
              ".sk-estimator-doc-link.fitted:hover,\n",
              "div.sk-label-container:hover .sk-estimator-doc-link.fitted:hover,\n",
              ".sk-estimator-doc-link.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "/* Span, style for the box shown on hovering the info icon */\n",
              ".sk-estimator-doc-link span {\n",
              "  display: none;\n",
              "  z-index: 9999;\n",
              "  position: relative;\n",
              "  font-weight: normal;\n",
              "  right: .2ex;\n",
              "  padding: .5ex;\n",
              "  margin: .5ex;\n",
              "  width: min-content;\n",
              "  min-width: 20ex;\n",
              "  max-width: 50ex;\n",
              "  color: var(--sklearn-color-text);\n",
              "  box-shadow: 2pt 2pt 4pt #999;\n",
              "  /* unfitted */\n",
              "  background: var(--sklearn-color-unfitted-level-0);\n",
              "  border: .5pt solid var(--sklearn-color-unfitted-level-3);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link.fitted span {\n",
              "  /* fitted */\n",
              "  background: var(--sklearn-color-fitted-level-0);\n",
              "  border: var(--sklearn-color-fitted-level-3);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link:hover span {\n",
              "  display: block;\n",
              "}\n",
              "\n",
              "/* \"?\"-specific style due to the `<a>` HTML tag */\n",
              "\n",
              "#sk-container-id-7 a.estimator_doc_link {\n",
              "  float: right;\n",
              "  font-size: 1rem;\n",
              "  line-height: 1em;\n",
              "  font-family: monospace;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  border-radius: 1rem;\n",
              "  height: 1rem;\n",
              "  width: 1rem;\n",
              "  text-decoration: none;\n",
              "  /* unfitted */\n",
              "  color: var(--sklearn-color-unfitted-level-1);\n",
              "  border: var(--sklearn-color-unfitted-level-1) 1pt solid;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 a.estimator_doc_link.fitted {\n",
              "  /* fitted */\n",
              "  border: var(--sklearn-color-fitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-fitted-level-1);\n",
              "}\n",
              "\n",
              "/* On hover */\n",
              "#sk-container-id-7 a.estimator_doc_link:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "#sk-container-id-7 a.estimator_doc_link.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-3);\n",
              "}\n",
              "</style><div id=\"sk-container-id-7\" class=\"sk-top-container\"><div class=\"sk-text-repr-fallback\"><pre>Pipeline(steps=[(&#x27;preprocessor&#x27;,\n",
              "                 ColumnTransformer(transformers=[(&#x27;scaling&#x27;, MinMaxScaler(),\n",
              "                                                  [&#x27;SqFt&#x27;, &#x27;Bathrooms&#x27;,\n",
              "                                                   &#x27;Bedrooms&#x27;, &#x27;Offers&#x27;]),\n",
              "                                                 (&#x27;onehot&#x27;, OneHotEncoder(),\n",
              "                                                  [&#x27;Brick&#x27;, &#x27;Neighborhood&#x27;])])),\n",
              "                (&#x27;regressor&#x27;, LinearRegression())])</pre><b>In a Jupyter environment, please rerun this cell to show the HTML representation or trust the notebook. <br />On GitHub, the HTML representation is unable to render, please try loading this page with nbviewer.org.</b></div><div class=\"sk-container\" hidden><div class=\"sk-item sk-dashed-wrapped\"><div class=\"sk-label-container\"><div class=\"sk-label fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-19\" type=\"checkbox\" ><label for=\"sk-estimator-id-19\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>Pipeline</div></div><div><a class=\"sk-estimator-doc-link fitted\" rel=\"noreferrer\" target=\"_blank\" href=\"https://scikit-learn.org/1.6/modules/generated/sklearn.pipeline.Pipeline.html\">?<span>Documentation for Pipeline</span></a><span class=\"sk-estimator-doc-link fitted\">i<span>Fitted</span></span></div></label><div class=\"sk-toggleable__content fitted\"><pre>Pipeline(steps=[(&#x27;preprocessor&#x27;,\n",
              "                 ColumnTransformer(transformers=[(&#x27;scaling&#x27;, MinMaxScaler(),\n",
              "                                                  [&#x27;SqFt&#x27;, &#x27;Bathrooms&#x27;,\n",
              "                                                   &#x27;Bedrooms&#x27;, &#x27;Offers&#x27;]),\n",
              "                                                 (&#x27;onehot&#x27;, OneHotEncoder(),\n",
              "                                                  [&#x27;Brick&#x27;, &#x27;Neighborhood&#x27;])])),\n",
              "                (&#x27;regressor&#x27;, LinearRegression())])</pre></div> </div></div><div class=\"sk-serial\"><div class=\"sk-item sk-dashed-wrapped\"><div class=\"sk-label-container\"><div class=\"sk-label fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-20\" type=\"checkbox\" ><label for=\"sk-estimator-id-20\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>preprocessor: ColumnTransformer</div></div><div><a class=\"sk-estimator-doc-link fitted\" rel=\"noreferrer\" target=\"_blank\" href=\"https://scikit-learn.org/1.6/modules/generated/sklearn.compose.ColumnTransformer.html\">?<span>Documentation for preprocessor: ColumnTransformer</span></a></div></label><div class=\"sk-toggleable__content fitted\"><pre>ColumnTransformer(transformers=[(&#x27;scaling&#x27;, MinMaxScaler(),\n",
              "                                 [&#x27;SqFt&#x27;, &#x27;Bathrooms&#x27;, &#x27;Bedrooms&#x27;, &#x27;Offers&#x27;]),\n",
              "                                (&#x27;onehot&#x27;, OneHotEncoder(),\n",
              "                                 [&#x27;Brick&#x27;, &#x27;Neighborhood&#x27;])])</pre></div> </div></div><div class=\"sk-parallel\"><div class=\"sk-parallel-item\"><div class=\"sk-item\"><div class=\"sk-label-container\"><div class=\"sk-label fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-21\" type=\"checkbox\" ><label for=\"sk-estimator-id-21\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>scaling</div></div></label><div class=\"sk-toggleable__content fitted\"><pre>[&#x27;SqFt&#x27;, &#x27;Bathrooms&#x27;, &#x27;Bedrooms&#x27;, &#x27;Offers&#x27;]</pre></div> </div></div><div class=\"sk-serial\"><div class=\"sk-item\"><div class=\"sk-estimator fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-22\" type=\"checkbox\" ><label for=\"sk-estimator-id-22\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>MinMaxScaler</div></div><div><a class=\"sk-estimator-doc-link fitted\" rel=\"noreferrer\" target=\"_blank\" href=\"https://scikit-learn.org/1.6/modules/generated/sklearn.preprocessing.MinMaxScaler.html\">?<span>Documentation for MinMaxScaler</span></a></div></label><div class=\"sk-toggleable__content fitted\"><pre>MinMaxScaler()</pre></div> </div></div></div></div></div><div class=\"sk-parallel-item\"><div class=\"sk-item\"><div class=\"sk-label-container\"><div class=\"sk-label fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-23\" type=\"checkbox\" ><label for=\"sk-estimator-id-23\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>onehot</div></div></label><div class=\"sk-toggleable__content fitted\"><pre>[&#x27;Brick&#x27;, &#x27;Neighborhood&#x27;]</pre></div> </div></div><div class=\"sk-serial\"><div class=\"sk-item\"><div class=\"sk-estimator fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-24\" type=\"checkbox\" ><label for=\"sk-estimator-id-24\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>OneHotEncoder</div></div><div><a class=\"sk-estimator-doc-link fitted\" rel=\"noreferrer\" target=\"_blank\" href=\"https://scikit-learn.org/1.6/modules/generated/sklearn.preprocessing.OneHotEncoder.html\">?<span>Documentation for OneHotEncoder</span></a></div></label><div class=\"sk-toggleable__content fitted\"><pre>OneHotEncoder()</pre></div> </div></div></div></div></div></div></div><div class=\"sk-item\"><div class=\"sk-estimator fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-25\" type=\"checkbox\" ><label for=\"sk-estimator-id-25\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>LinearRegression</div></div><div><a class=\"sk-estimator-doc-link fitted\" rel=\"noreferrer\" target=\"_blank\" href=\"https://scikit-learn.org/1.6/modules/generated/sklearn.linear_model.LinearRegression.html\">?<span>Documentation for LinearRegression</span></a></div></label><div class=\"sk-toggleable__content fitted\"><pre>LinearRegression()</pre></div> </div></div></div></div></div></div>"
            ]
          },
          "metadata": {},
          "execution_count": 197
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "y_pred=model.predict(X_test)"
      ],
      "metadata": {
        "id": "MAZ6klWHwo_a"
      },
      "execution_count": 198,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "print(\"Mean Squared Error:\", mean_squared_error(y_test, y_pred))\n",
        "print(\"R-squared Score:\", r2_score(y_test, y_pred))\n",
        "print(\"Mean Absolute Error:\", mean_absolute_error(y_test, y_pred))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "uZE7p9elwtbv",
        "outputId": "a3927c96-646c-48f5-de0a-1902272a0267"
      },
      "execution_count": 199,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Mean Squared Error: 114170418.45453855\n",
            "R-squared Score: 0.8062934622232132\n",
            "Mean Absolute Error: 8901.290743964866\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Day 8 (Logistic Regression)"
      ],
      "metadata": {
        "id": "zuniv7m7tm0o"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "# Logistic Regression  is a classification supervised machine learning algorithm it is used classification problem\n",
        "# It predicts the probability the observation belongs to particular  class or not.\n",
        "# Eg: spam or npot spam , diesease or not ,pass or fail,fraud  or genuine, purchase or not purchased,true or flase.\n",
        "\n",
        "# why not linear regression?\n",
        "# suppose if we want to predict wether a candidate is pass or fail from the given data.\n",
        "# Using linear regression from the above data it predicts the continious values which acceses the limits.\n",
        "# The limit for logistic regression is between 0 to 1.\n",
        "# As the values will be invalid by genrating using linear rgression,hence we need the logistic regression.\n",
        "# when predicted output as well as, actual output both are treated as same than we called as true positive.\n"
      ],
      "metadata": {
        "id": "cEclMhgetorI"
      },
      "execution_count": 286,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "# write a program in python to demostrate logistic regression\n",
        "import numpy as np\n",
        "import pandas as pd\n",
        "import matplotlib.pyplot as plt\n",
        "import seaborn as sns\n",
        "from sklearn.model_selection import train_test_split\n",
        "from sklearn.linear_model import LogisticRegression\n",
        "from sklearn.metrics import accuracy_score,confusion_matrix,classification_report,recall_score,f1_score,precision_score,roc_auc_score\n",
        "\n",
        "data ={\n",
        "    \"Hours\":[1,2,3,4,5,6,7,8,9,10],\n",
        "    \"Pass\":[0,0,0,0,0,0,1,1,1,1]\n",
        "}\n",
        "df=pd.DataFrame(data)"
      ],
      "metadata": {
        "id": "8va23JWu_S_9"
      },
      "execution_count": 287,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "df.head()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 206
        },
        "id": "RFOUesbBFiOS",
        "outputId": "7483b5b4-8293-44a6-b2e9-6e6efd041431"
      },
      "execution_count": 289,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "   Hours  Pass\n",
              "0      1     0\n",
              "1      2     0\n",
              "2      3     0\n",
              "3      4     0\n",
              "4      5     0"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-c6a9e5d4-e9c9-414d-911b-4c4a9859f1b0\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>Hours</th>\n",
              "      <th>Pass</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>1</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>2</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>3</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>3</th>\n",
              "      <td>4</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>4</th>\n",
              "      <td>5</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-c6a9e5d4-e9c9-414d-911b-4c4a9859f1b0')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-c6a9e5d4-e9c9-414d-911b-4c4a9859f1b0 button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-c6a9e5d4-e9c9-414d-911b-4c4a9859f1b0');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "variable_name": "df",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 10,\n  \"fields\": [\n    {\n      \"column\": \"Hours\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 3,\n        \"min\": 1,\n        \"max\": 10,\n        \"num_unique_values\": 10,\n        \"samples\": [\n          9,\n          2,\n          6\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Pass\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 0,\n        \"max\": 1,\n        \"num_unique_values\": 2,\n        \"samples\": [\n          1,\n          0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 289
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(df)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "aDD_ZT7qAFRP",
        "outputId": "6e07e937-9f92-4d13-f419-8711914c3724"
      },
      "execution_count": 290,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "   Hours  Pass\n",
            "0      1     0\n",
            "1      2     0\n",
            "2      3     0\n",
            "3      4     0\n",
            "4      5     0\n",
            "5      6     0\n",
            "6      7     1\n",
            "7      8     1\n",
            "8      9     1\n",
            "9     10     1\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "x=df[['Hours']]\n",
        "y=df[['Pass']]\n",
        "x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=42)"
      ],
      "metadata": {
        "id": "WNNVjePXAW_g"
      },
      "execution_count": 291,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "#Train the model\n",
        "model=LogisticRegression()\n",
        "model.fit(x_train,y_train)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 135
        },
        "id": "MsvwvbfUAsgO",
        "outputId": "1ab0e4ec-ca4b-41d8-fd39-1238593194a1"
      },
      "execution_count": 292,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.12/dist-packages/sklearn/utils/validation.py:1408: DataConversionWarning: A column-vector y was passed when a 1d array was expected. Please change the shape of y to (n_samples, ), for example using ravel().\n",
            "  y = column_or_1d(y, warn=True)\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "LogisticRegression()"
            ],
            "text/html": [
              "<style>#sk-container-id-13 {\n",
              "  /* Definition of color scheme common for light and dark mode */\n",
              "  --sklearn-color-text: #000;\n",
              "  --sklearn-color-text-muted: #666;\n",
              "  --sklearn-color-line: gray;\n",
              "  /* Definition of color scheme for unfitted estimators */\n",
              "  --sklearn-color-unfitted-level-0: #fff5e6;\n",
              "  --sklearn-color-unfitted-level-1: #f6e4d2;\n",
              "  --sklearn-color-unfitted-level-2: #ffe0b3;\n",
              "  --sklearn-color-unfitted-level-3: chocolate;\n",
              "  /* Definition of color scheme for fitted estimators */\n",
              "  --sklearn-color-fitted-level-0: #f0f8ff;\n",
              "  --sklearn-color-fitted-level-1: #d4ebff;\n",
              "  --sklearn-color-fitted-level-2: #b3dbfd;\n",
              "  --sklearn-color-fitted-level-3: cornflowerblue;\n",
              "\n",
              "  /* Specific color for light theme */\n",
              "  --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));\n",
              "  --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, white)));\n",
              "  --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));\n",
              "  --sklearn-color-icon: #696969;\n",
              "\n",
              "  @media (prefers-color-scheme: dark) {\n",
              "    /* Redefinition of color scheme for dark theme */\n",
              "    --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));\n",
              "    --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, #111)));\n",
              "    --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));\n",
              "    --sklearn-color-icon: #878787;\n",
              "  }\n",
              "}\n",
              "\n",
              "#sk-container-id-13 {\n",
              "  color: var(--sklearn-color-text);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 pre {\n",
              "  padding: 0;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 input.sk-hidden--visually {\n",
              "  border: 0;\n",
              "  clip: rect(1px 1px 1px 1px);\n",
              "  clip: rect(1px, 1px, 1px, 1px);\n",
              "  height: 1px;\n",
              "  margin: -1px;\n",
              "  overflow: hidden;\n",
              "  padding: 0;\n",
              "  position: absolute;\n",
              "  width: 1px;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-dashed-wrapped {\n",
              "  border: 1px dashed var(--sklearn-color-line);\n",
              "  margin: 0 0.4em 0.5em 0.4em;\n",
              "  box-sizing: border-box;\n",
              "  padding-bottom: 0.4em;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-container {\n",
              "  /* jupyter's `normalize.less` sets `[hidden] { display: none; }`\n",
              "     but bootstrap.min.css set `[hidden] { display: none !important; }`\n",
              "     so we also need the `!important` here to be able to override the\n",
              "     default hidden behavior on the sphinx rendered scikit-learn.org.\n",
              "     See: https://github.com/scikit-learn/scikit-learn/issues/21755 */\n",
              "  display: inline-block !important;\n",
              "  position: relative;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-text-repr-fallback {\n",
              "  display: none;\n",
              "}\n",
              "\n",
              "div.sk-parallel-item,\n",
              "div.sk-serial,\n",
              "div.sk-item {\n",
              "  /* draw centered vertical line to link estimators */\n",
              "  background-image: linear-gradient(var(--sklearn-color-text-on-default-background), var(--sklearn-color-text-on-default-background));\n",
              "  background-size: 2px 100%;\n",
              "  background-repeat: no-repeat;\n",
              "  background-position: center center;\n",
              "}\n",
              "\n",
              "/* Parallel-specific style estimator block */\n",
              "\n",
              "#sk-container-id-13 div.sk-parallel-item::after {\n",
              "  content: \"\";\n",
              "  width: 100%;\n",
              "  border-bottom: 2px solid var(--sklearn-color-text-on-default-background);\n",
              "  flex-grow: 1;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-parallel {\n",
              "  display: flex;\n",
              "  align-items: stretch;\n",
              "  justify-content: center;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  position: relative;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-parallel-item {\n",
              "  display: flex;\n",
              "  flex-direction: column;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-parallel-item:first-child::after {\n",
              "  align-self: flex-end;\n",
              "  width: 50%;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-parallel-item:last-child::after {\n",
              "  align-self: flex-start;\n",
              "  width: 50%;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-parallel-item:only-child::after {\n",
              "  width: 0;\n",
              "}\n",
              "\n",
              "/* Serial-specific style estimator block */\n",
              "\n",
              "#sk-container-id-13 div.sk-serial {\n",
              "  display: flex;\n",
              "  flex-direction: column;\n",
              "  align-items: center;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  padding-right: 1em;\n",
              "  padding-left: 1em;\n",
              "}\n",
              "\n",
              "\n",
              "/* Toggleable style: style used for estimator/Pipeline/ColumnTransformer box that is\n",
              "clickable and can be expanded/collapsed.\n",
              "- Pipeline and ColumnTransformer use this feature and define the default style\n",
              "- Estimators will overwrite some part of the style using the `sk-estimator` class\n",
              "*/\n",
              "\n",
              "/* Pipeline and ColumnTransformer style (default) */\n",
              "\n",
              "#sk-container-id-13 div.sk-toggleable {\n",
              "  /* Default theme specific background. It is overwritten whether we have a\n",
              "  specific estimator or a Pipeline/ColumnTransformer */\n",
              "  background-color: var(--sklearn-color-background);\n",
              "}\n",
              "\n",
              "/* Toggleable label */\n",
              "#sk-container-id-13 label.sk-toggleable__label {\n",
              "  cursor: pointer;\n",
              "  display: flex;\n",
              "  width: 100%;\n",
              "  margin-bottom: 0;\n",
              "  padding: 0.5em;\n",
              "  box-sizing: border-box;\n",
              "  text-align: center;\n",
              "  align-items: start;\n",
              "  justify-content: space-between;\n",
              "  gap: 0.5em;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 label.sk-toggleable__label .caption {\n",
              "  font-size: 0.6rem;\n",
              "  font-weight: lighter;\n",
              "  color: var(--sklearn-color-text-muted);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 label.sk-toggleable__label-arrow:before {\n",
              "  /* Arrow on the left of the label */\n",
              "  content: \"▸\";\n",
              "  float: left;\n",
              "  margin-right: 0.25em;\n",
              "  color: var(--sklearn-color-icon);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 label.sk-toggleable__label-arrow:hover:before {\n",
              "  color: var(--sklearn-color-text);\n",
              "}\n",
              "\n",
              "/* Toggleable content - dropdown */\n",
              "\n",
              "#sk-container-id-13 div.sk-toggleable__content {\n",
              "  max-height: 0;\n",
              "  max-width: 0;\n",
              "  overflow: hidden;\n",
              "  text-align: left;\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-toggleable__content.fitted {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-toggleable__content pre {\n",
              "  margin: 0.2em;\n",
              "  border-radius: 0.25em;\n",
              "  color: var(--sklearn-color-text);\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-toggleable__content.fitted pre {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 input.sk-toggleable__control:checked~div.sk-toggleable__content {\n",
              "  /* Expand drop-down */\n",
              "  max-height: 200px;\n",
              "  max-width: 100%;\n",
              "  overflow: auto;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 input.sk-toggleable__control:checked~label.sk-toggleable__label-arrow:before {\n",
              "  content: \"▾\";\n",
              "}\n",
              "\n",
              "/* Pipeline/ColumnTransformer-specific style */\n",
              "\n",
              "#sk-container-id-13 div.sk-label input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-label.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Estimator-specific style */\n",
              "\n",
              "/* Colorize estimator box */\n",
              "#sk-container-id-13 div.sk-estimator input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-estimator.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-label label.sk-toggleable__label,\n",
              "#sk-container-id-13 div.sk-label label {\n",
              "  /* The background is the default theme color */\n",
              "  color: var(--sklearn-color-text-on-default-background);\n",
              "}\n",
              "\n",
              "/* On hover, darken the color of the background */\n",
              "#sk-container-id-13 div.sk-label:hover label.sk-toggleable__label {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "/* Label box, darken color on hover, fitted */\n",
              "#sk-container-id-13 div.sk-label.fitted:hover label.sk-toggleable__label.fitted {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Estimator label */\n",
              "\n",
              "#sk-container-id-13 div.sk-label label {\n",
              "  font-family: monospace;\n",
              "  font-weight: bold;\n",
              "  display: inline-block;\n",
              "  line-height: 1.2em;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-label-container {\n",
              "  text-align: center;\n",
              "}\n",
              "\n",
              "/* Estimator-specific */\n",
              "#sk-container-id-13 div.sk-estimator {\n",
              "  font-family: monospace;\n",
              "  border: 1px dotted var(--sklearn-color-border-box);\n",
              "  border-radius: 0.25em;\n",
              "  box-sizing: border-box;\n",
              "  margin-bottom: 0.5em;\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-estimator.fitted {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "/* on hover */\n",
              "#sk-container-id-13 div.sk-estimator:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-13 div.sk-estimator.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Specification for estimator info (e.g. \"i\" and \"?\") */\n",
              "\n",
              "/* Common style for \"i\" and \"?\" */\n",
              "\n",
              ".sk-estimator-doc-link,\n",
              "a:link.sk-estimator-doc-link,\n",
              "a:visited.sk-estimator-doc-link {\n",
              "  float: right;\n",
              "  font-size: smaller;\n",
              "  line-height: 1em;\n",
              "  font-family: monospace;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  border-radius: 1em;\n",
              "  height: 1em;\n",
              "  width: 1em;\n",
              "  text-decoration: none !important;\n",
              "  margin-left: 0.5em;\n",
              "  text-align: center;\n",
              "  /* unfitted */\n",
              "  border: var(--sklearn-color-unfitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-unfitted-level-1);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link.fitted,\n",
              "a:link.sk-estimator-doc-link.fitted,\n",
              "a:visited.sk-estimator-doc-link.fitted {\n",
              "  /* fitted */\n",
              "  border: var(--sklearn-color-fitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-fitted-level-1);\n",
              "}\n",
              "\n",
              "/* On hover */\n",
              "div.sk-estimator:hover .sk-estimator-doc-link:hover,\n",
              ".sk-estimator-doc-link:hover,\n",
              "div.sk-label-container:hover .sk-estimator-doc-link:hover,\n",
              ".sk-estimator-doc-link:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "div.sk-estimator.fitted:hover .sk-estimator-doc-link.fitted:hover,\n",
              ".sk-estimator-doc-link.fitted:hover,\n",
              "div.sk-label-container:hover .sk-estimator-doc-link.fitted:hover,\n",
              ".sk-estimator-doc-link.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "/* Span, style for the box shown on hovering the info icon */\n",
              ".sk-estimator-doc-link span {\n",
              "  display: none;\n",
              "  z-index: 9999;\n",
              "  position: relative;\n",
              "  font-weight: normal;\n",
              "  right: .2ex;\n",
              "  padding: .5ex;\n",
              "  margin: .5ex;\n",
              "  width: min-content;\n",
              "  min-width: 20ex;\n",
              "  max-width: 50ex;\n",
              "  color: var(--sklearn-color-text);\n",
              "  box-shadow: 2pt 2pt 4pt #999;\n",
              "  /* unfitted */\n",
              "  background: var(--sklearn-color-unfitted-level-0);\n",
              "  border: .5pt solid var(--sklearn-color-unfitted-level-3);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link.fitted span {\n",
              "  /* fitted */\n",
              "  background: var(--sklearn-color-fitted-level-0);\n",
              "  border: var(--sklearn-color-fitted-level-3);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link:hover span {\n",
              "  display: block;\n",
              "}\n",
              "\n",
              "/* \"?\"-specific style due to the `<a>` HTML tag */\n",
              "\n",
              "#sk-container-id-13 a.estimator_doc_link {\n",
              "  float: right;\n",
              "  font-size: 1rem;\n",
              "  line-height: 1em;\n",
              "  font-family: monospace;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  border-radius: 1rem;\n",
              "  height: 1rem;\n",
              "  width: 1rem;\n",
              "  text-decoration: none;\n",
              "  /* unfitted */\n",
              "  color: var(--sklearn-color-unfitted-level-1);\n",
              "  border: var(--sklearn-color-unfitted-level-1) 1pt solid;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 a.estimator_doc_link.fitted {\n",
              "  /* fitted */\n",
              "  border: var(--sklearn-color-fitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-fitted-level-1);\n",
              "}\n",
              "\n",
              "/* On hover */\n",
              "#sk-container-id-13 a.estimator_doc_link:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "#sk-container-id-13 a.estimator_doc_link.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-3);\n",
              "}\n",
              "</style><div id=\"sk-container-id-13\" class=\"sk-top-container\"><div class=\"sk-text-repr-fallback\"><pre>LogisticRegression()</pre><b>In a Jupyter environment, please rerun this cell to show the HTML representation or trust the notebook. <br />On GitHub, the HTML representation is unable to render, please try loading this page with nbviewer.org.</b></div><div class=\"sk-container\" hidden><div class=\"sk-item\"><div class=\"sk-estimator fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-31\" type=\"checkbox\" checked><label for=\"sk-estimator-id-31\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>LogisticRegression</div></div><div><a class=\"sk-estimator-doc-link fitted\" rel=\"noreferrer\" target=\"_blank\" href=\"https://scikit-learn.org/1.6/modules/generated/sklearn.linear_model.LogisticRegression.html\">?<span>Documentation for LogisticRegression</span></a><span class=\"sk-estimator-doc-link fitted\">i<span>Fitted</span></span></div></label><div class=\"sk-toggleable__content fitted\"><pre>LogisticRegression()</pre></div> </div></div></div></div>"
            ]
          },
          "metadata": {},
          "execution_count": 292
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Prediction\n",
        "prediction = model.predict(x_test)\n",
        "print(prediction)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "zWt4krDcAxuy",
        "outputId": "2d2bd10a-b1f2-4bea-ccf5-d920399ba1e9"
      },
      "execution_count": 293,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[1 0]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#probability\n",
        "probability=model.predict_proba(x_test)\n",
        "print(probability)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "ICvIuVtJBRJ0",
        "outputId": "47ac6481-ef71-481c-e355-34393db7860b"
      },
      "execution_count": 294,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[0.06155034 0.93844966]\n",
            " [0.99398523 0.00601477]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#evalution matrics\n",
        "\n",
        "accuracy=accuracy_score(y_test,prediction)\n",
        "print(accuracy)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "1CHxhAlWB-wO",
        "outputId": "3c4202b9-cd7a-4e41-dcfa-99d38975c1b4"
      },
      "execution_count": 295,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#confusion matrix\n",
        "confusion=confusion_matrix(y_test,prediction)\n",
        "print(confusion)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "iK-4H0TLCHKQ",
        "outputId": "7628d0d9-f0a3-4b16-e018-069d37f9ae5c"
      },
      "execution_count": 296,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[1 0]\n",
            " [0 1]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#precision\n",
        "precision=precision_score(y_test,prediction)\n",
        "print(precision)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "W7mdSvbpCK-D",
        "outputId": "a96624af-31cc-4b97-e566-aa244687bedf"
      },
      "execution_count": 297,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#recall\n",
        "recall=recall_score(y_test,prediction)\n",
        "print(recall)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "hath3rAPCT-8",
        "outputId": "d40287a7-d860-4ec7-9a11-0399acce5452"
      },
      "execution_count": 298,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#f1_score\n",
        "f1=f1_score(y_test,prediction)\n",
        "print(f1)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "SrCRK_yACVkg",
        "outputId": "63573d84-5042-4a84-9102-e83e8de530a7"
      },
      "execution_count": 299,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#roc_auc\n",
        "roc_auc=roc_auc_score(y_test,prediction)\n",
        "print(roc_auc)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "IVk6vGU7Ci07",
        "outputId": "a6f60cdf-d61f-45cb-b50e-145f03f71aef"
      },
      "execution_count": 300,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "hours=7\n",
        "prediction=model.predict([[hours]])\n",
        "print(prediction)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "9CQp0RNwCmHX",
        "outputId": "806dde7c-ff8b-4df4-cc60-b434507b8614"
      },
      "execution_count": 301,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[1]\n"
          ]
        },
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.12/dist-packages/sklearn/utils/validation.py:2739: UserWarning: X does not have valid feature names, but LogisticRegression was fitted with feature names\n",
            "  warnings.warn(\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "from sklearn.metrics import RocCurveDisplay\n",
        "import matplotlib.pyplot as plt\n",
        "\n",
        "prediction = model.predict(x_test)\n",
        "RocCurveDisplay.from_predictions(y_test,prediction)\n",
        "plt.title(\"ROC Curve\")\n",
        "plt.xlabel(\"False Positive Rate\")\n",
        "plt.ylabel(\"True Positive Rate\")\n",
        "plt.show()"
      ],
      "metadata": {
        "id": "5HMKnGVyDrp0",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 472
        },
        "outputId": "972a5d1e-6149-4edf-9557-88c2e4858ecc"
      },
      "execution_count": 302,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 640x480 with 1 Axes>"
            ],
            "image/png": "iVBORw0KGgoAAAANSUhEUgAAAcAAAAHHCAYAAAAoIIjLAAAAOnRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjEwLjAsIGh0dHBzOi8vbWF0cGxvdGxpYi5vcmcvlHJYcgAAAAlwSFlzAAAPYQAAD2EBqD+naQAAQ5tJREFUeJzt3XlcVPX+P/DXsMwAsnqRtUnccEkT1CRwoZTELM2rJaYpUqmZmkmmuOKSS2mmuaapZFqgpuVVw6ukpURZIG4opkCuoHxVEJBt5vP7ox/nOrLI4AwjnNfz8TiP63zm8znnPZ+b8/KcOYtCCCFAREQkM2amLoCIiMgUGIBERCRLDEAiIpIlBiAREckSA5CIiGSJAUhERLLEACQiIlliABIRkSwxAImISJYYgEREJEsMQKJqiIqKgkKhkBYLCwt4enpixIgRuHr1aoVjhBD4+uuv0b17dzg6OsLGxgbt2rXD3LlzkZ+fX+m2du3ahRdffBHOzs5QKpXw8PDAoEGD8NNPP1Wr1sLCQnz22Wfw8/ODg4MDrKys4O3tjXHjxuH8+fM1+vxE9ZGC9wIlerioqCiEhYVh7ty5aNKkCQoLC/Hbb78hKioKXl5eOH36NKysrKT+Go0GQ4YMwbZt29CtWzcMGDAANjY2OHLkCL755hu0adMGBw8ehKurqzRGCIE333wTUVFR8PX1xauvvgo3Nzdcv34du3btQmJiIuLj4xEQEFBpndnZ2ejduzcSExPx8ssvIygoCLa2tkhNTUV0dDQyMzNRXFxs1LkiqjMEET3Upk2bBADxxx9/6LRPmTJFABAxMTE67QsWLBAAxKRJk8qta/fu3cLMzEz07t1bp33x4sUCgHj//feFVqstN27z5s3i999/r7LOl156SZiZmYkdO3aUe6+wsFB88MEHVY6vrpKSElFUVGSQdRGZCgOQqBoqC8A9e/YIAGLBggVSW0FBgXBychLe3t6ipKSkwvWFhYUJACIhIUEa07BhQ9GqVStRWlpaoxp/++03AUCMHDmyWv0DAwNFYGBgufbQ0FDRuHFj6XV6eroAIBYvXiw+++wz0bRpU2FmZiZ+++03YW5uLmbPnl1uHefOnRMAxIoVK6S227dviwkTJognnnhCKJVK0axZM7Fo0SKh0Wj0/qxEhsDfAIkeQUZGBgDAyclJajt69Chu376NIUOGwMLCosJxw4cPBwDs2bNHGnPr1i0MGTIE5ubmNapl9+7dAIBhw4bVaPzDbNq0CStWrMCoUaPw6aefwt3dHYGBgdi2bVu5vjExMTA3N8drr70GACgoKEBgYCC2bNmC4cOH4/PPP0eXLl0wdepUhIeHG6Veooep+G8nEVUoJycH2dnZKCwsxO+//445c+ZApVLh5ZdflvqkpKQAANq3b1/pesreO3v2rM7/tmvXrsa1GWIdVbly5QouXLiARo0aSW0hISEYPXo0Tp8+jbZt20rtMTExCAwMlH7jXLp0KS5evIjjx4+jRYsWAIDRo0fDw8MDixcvxgcffAC1Wm2Uuokqwz1AIj0EBQWhUaNGUKvVePXVV9GgQQPs3r0bTzzxhNTn7t27AAA7O7tK11P2Xm5urs7/VjXmYQyxjqoMHDhQJ/wAYMCAAbCwsEBMTIzUdvr0aaSkpCAkJERq2759O7p16wYnJydkZ2dLS1BQEDQaDX755Rej1ExUFe4BEulh1apV8Pb2Rk5ODjZu3IhffvkFKpVKp09ZAJUFYUUeDEl7e/uHjnmY+9fh6OhY4/VUpkmTJuXanJ2d0bNnT2zbtg3z5s0D8M/en4WFBQYMGCD1++uvv3Dy5MlyAVrmxo0bBq+X6GEYgER66Ny5Mzp16gQA6N+/P7p27YohQ4YgNTUVtra2AIDWrVsDAE6ePIn+/ftXuJ6TJ08CANq0aQMAaNWqFQDg1KlTlY55mPvX0a1bt4f2VygUEBVcBaXRaCrsb21tXWH74MGDERYWhuTkZPj4+GDbtm3o2bMnnJ2dpT5arRYvvPACJk+eXOE6vL29H1ovkaHxEChRDZmbm2PhwoW4du0aVq5cKbV37doVjo6O+OabbyoNk82bNwOA9Nth165d4eTkhG+//bbSMQ/Tt29fAMCWLVuq1d/JyQl37twp1/7333/rtd3+/ftDqVQiJiYGycnJOH/+PAYPHqzTp1mzZsjLy0NQUFCFy5NPPqnXNokMgQFI9Aiee+45dO7cGcuWLUNhYSEAwMbGBpMmTUJqaiqmT59ebszevXsRFRWF4OBgPPvss9KYKVOm4OzZs5gyZUqFe2ZbtmzBsWPHKq3F398fvXv3xpdffonvv/++3PvFxcWYNGmS9LpZs2Y4d+4cbt68KbWdOHEC8fHx1f78AODo6Ijg4GBs27YN0dHRUCqV5fZiBw0ahISEBOzfv7/c+Dt37qC0tFSvbRIZhKmvwyCqCyq7DlAIIbZv3y4AiDVr1khtpaWlYuDAgQKA6N69u1i+fLlYt26dGD58uDAzMxNPPfWUyMzM1FmPRqMRw4YNEwBEhw4dxIIFC8TGjRvFggULROfOnQUA8euvv1ZZ540bN4SPj49QKBSiX79+Yvny5eLLL78UU6ZMEY0bNxZKpVLqm5KSIszMzISvr69YuXKlmDVrlnBxcRHt2rWr9DrAymzZskUAEHZ2dqJv377l3s/PzxcdOnQQFhYW4u233xZr1qwRS5YsEaGhoaJBgwbi5s2bVX4uImNgABJVQ1UBqNFoRLNmzUSzZs10LmLXaDRi06ZNokuXLsLe3l5YWVmJp556SsyZM0fk5eVVuq0dO3aIXr16iYYNGwoLCwvh7u4uQkJCxOHDh6tVa0FBgViyZIl45plnhK2trVAqlaJFixZi/Pjx4sKFCzp9t2zZIpo2bSqUSqXw8fER+/fvr/JC+Mrk5uYKa2trAUBs2bKlwj53794VU6dOFc2bNxdKpVI4OzuLgIAAsWTJElFcXFytz0ZkSLwXKBERyRJ/AyQiIlliABIRkSwxAImISJYYgEREJEsMQCIikiUGIBERyZJJ7wX6yy+/YPHixUhMTMT169exa9euh94H8fDhwwgPD8eZM2egVqsxY8YMjBgxotrb1Gq1uHbtGuzs7KBQKB7tAxARUa0TQuDu3bvw8PCAmVnN9+NMGoD5+flo37493nzzTZ07x1cmPT0dL730Et555x1s3boVcXFxePvtt+Hu7o7g4OBqbfPatWt87hgRUT1w+fJlnUeR6euxuRBeoVA8dA9wypQp2Lt3L06fPi21DR48GHfu3EFsbGy1tpOTkwNHR0dcvnxZenwMERHVHbm5uVCr1bhz5w4cHBxqvJ469TikhIQEBAUF6bQFBwfj/fffr/Y6yg572tvbw97eHkII3Cup2d33iYio9lhbmuv8dPWoP2PVqQDMzMyEq6urTpurqytyc3Nx7969Cp9XVlRUhKKiIul12VOzgX+OI7+6NgGJf982XtFERGQQKXODYaM0XGzV+7NAFy5cCAcHB2m5//e/eyUahh8RkUzVqT1ANzc3ZGVl6bRlZWXB3t6+0qdVT506FeHh4dLrsmPHD/pzRhBslOaGLZiIiAzG2tKw39F1KgD9/f2xb98+nbYDBw7A39+/0jEqlQoqleqh67ZRmht015qIiB5vJj0EmpeXh+TkZCQnJwP45zKH5ORkXLp0CcA/e2/Dhw+X+r/zzjtIS0vD5MmTce7cOaxevRrbtm3DxIkTTVE+ERHVYSYNwD///BO+vr7w9fUFAISHh8PX1xezZs0CAFy/fl0KQwBo0qQJ9u7diwMHDqB9+/b49NNP8eWXX1b7GkAiIqIyJj3m99xzz6GqyxCjoqIqHHP8+HEjVkVERHJQ788CJSIiqggDkIiIZIkBSEREssQAJCIiWWIAEhGRLDEAiYhIlhiAREQkSwxAIiKSJQYgERHJEgOQiIhkiQFIRESyxAAkIiJZYgASEZEsMQCJiEiWGIBERCRLDEAiIpIlBiAREckSA5CIiGSJAUhERLLEACQiIlliABIRkSwxAImISJYYgEREJEsMQCIikiUGIBERyRIDkIiIZIkBSEREssQAJCIiWWIAEhGRLDEAiYhIlhiAREQkSwxAIiKSJQYgERHJEgOQiIhkiQFIRESyxAAkIiJZYgASEZEsMQCJiEiWGIBERCRLDEAiIpIlBiAREckSA5CIiGSJAUhERLLEACQiIlliABIRkSwxAImISJYYgEREJEsMQCIikiUGIBERyRIDkIiIZIkBSEREssQAJCIiWWIAEhGRLDEAiYhIlhiAREQkSwxAIiKSJQYgERHJEgOQiIhkiQFIRESyxAAkIiJZYgASEZEsMQCJiEiWTB6Aq1atgpeXF6ysrODn54djx45V2X/ZsmVo2bIlrK2toVarMXHiRBQWFtZStUREVF+YNABjYmIQHh6OyMhIJCUloX379ggODsaNGzcq7P/NN98gIiICkZGROHv2LDZs2ICYmBhMmzatlisnIqK6zqQBuHTpUowcORJhYWFo06YN1q5dCxsbG2zcuLHC/r/++iu6dOmCIUOGwMvLC7169cLrr7/+0L1GIiKiB5ksAIuLi5GYmIigoKD/FWNmhqCgICQkJFQ4JiAgAImJiVLgpaWlYd++fejTp0+l2ykqKkJubq7OQkREZGGqDWdnZ0Oj0cDV1VWn3dXVFefOnatwzJAhQ5CdnY2uXbtCCIHS0lK88847VR4CXbhwIebMmWPQ2omIqO4z+Ukw+jh8+DAWLFiA1atXIykpCTt37sTevXsxb968SsdMnToVOTk50nL58uVarJiIiB5XJtsDdHZ2hrm5ObKysnTas7Ky4ObmVuGYmTNnYtiwYXj77bcBAO3atUN+fj5GjRqF6dOnw8ysfJ6rVCqoVCrDfwAiIqrTTLYHqFQq0bFjR8TFxUltWq0WcXFx8Pf3r3BMQUFBuZAzNzcHAAghjFcsERHVOybbAwSA8PBwhIaGolOnTujcuTOWLVuG/Px8hIWFAQCGDx8OT09PLFy4EADQt29fLF26FL6+vvDz88OFCxcwc+ZM9O3bVwpCIiKi6jBpAIaEhODmzZuYNWsWMjMz4ePjg9jYWOnEmEuXLuns8c2YMQMKhQIzZszA1atX0ahRI/Tt2xfz58831UcgIqI6SiFkduwwNzcXDg4OyMnJgYWVDdrM2g8ASJkbDBulSf89QERE1XD/97i9vX2N11OnzgIlIiIyFAYgERHJEgOQiIhkiQFIRESyxAAkIiJZYgASEZEsMQCJiEiWGIBERCRLDEAiIpIlBiAREckSA5CIiGSJAUhERLLEACQiIlliABIRkSwxAImISJYYgEREJEsMQCIikiUGIBERyRIDkIiIZIkBSEREssQAJCIiWWIAEhGRLDEAiYhIlhiAREQkSwxAIiKSJQYgERHJEgOQiIhkiQFIRESyxAAkIiJZYgASEZEsMQCJiEiWGIBERCRLDEAiIpIlBiAREckSA5CIiGSJAUhERLLEACQiIlliABIRkSwxAImISJYYgEREJEsMQCIikqVHCsDCwkJD1UFERFSr9A5ArVaLefPmwdPTE7a2tkhLSwMAzJw5Exs2bDB4gURERMagdwB+9NFHiIqKwieffAKlUim1t23bFl9++aVBiyMiIjIWvQNw8+bNWLduHYYOHQpzc3OpvX379jh37pxBiyMiIjIWvQPw6tWraN68ebl2rVaLkpISgxRFRERkbHoHYJs2bXDkyJFy7Tt27ICvr69BiiIiIjI2C30HzJo1C6Ghobh69Sq0Wi127tyJ1NRUbN68GXv27DFGjURERAan9x7gK6+8gv/85z84ePAgGjRogFmzZuHs2bP4z3/+gxdeeMEYNRIRERmc3nuAANCtWzccOHDA0LUQERHVGr33AJs2bYr/+7//K9d+584dNG3a1CBFERERGZveAZiRkQGNRlOuvaioCFevXjVIUURERMZW7UOgu3fvlv68f/9+ODg4SK81Gg3i4uLg5eVl0OKIiIiMpdoB2L9/fwCAQqFAaGioznuWlpbw8vLCp59+atDiiIiIjKXaAajVagEATZo0wR9//AFnZ2ejFUVERGRsep8Fmp6ebow6iIiIalWNLoPIz8/Hzz//jEuXLqG4uFjnvffee88ghRERERmT3gF4/Phx9OnTBwUFBcjPz0fDhg2RnZ0NGxsbuLi4MACJiKhO0PsyiIkTJ6Jv3764ffs2rK2t8dtvv+Hvv/9Gx44dsWTJEmPUSEREZHB6B2BycjI++OADmJmZwdzcHEVFRVCr1fjkk08wbdo0Y9RIRERkcHoHoKWlJczM/hnm4uKCS5cuAQAcHBxw+fJlw1ZHRERkJHoHoK+vL/744w8AQGBgIGbNmoWtW7fi/fffR9u2bfUuYNWqVfDy8oKVlRX8/Pxw7NixKvvfuXMHY8eOhbu7O1QqFby9vbFv3z69t0tERPKmdwAuWLAA7u7uAID58+fDyckJY8aMwc2bN/HFF1/ota6YmBiEh4cjMjISSUlJaN++PYKDg3Hjxo0K+xcXF+OFF15ARkYGduzYgdTUVKxfvx6enp76fgwiIpI5hRBCmGrjfn5+eOaZZ7By5UoA/1xsr1arMX78eERERJTrv3btWixevBjnzp2DpaVljbaZm5sLBwcH5OTkwMLKBm1m7QcApMwNho2yRleFEBFRLbr/e9ze3r7G69F7D7AySUlJePnll6vdv7i4GImJiQgKCvpfMWZmCAoKQkJCQoVjdu/eDX9/f4wdOxaurq5o27YtFixYUOHNuYmIiKqiVwDu378fkyZNwrRp05CWlgYAOHfuHPr3749nnnlGul1adWRnZ0Oj0cDV1VWn3dXVFZmZmRWOSUtLw44dO6DRaLBv3z7MnDkTn376KT766KNKt1NUVITc3FydhYiIqNoBuGHDBrz44ouIiorCxx9/jGeffRZbtmyBv78/3NzccPr0aaOfjKLVauHi4oJ169ahY8eOCAkJwfTp07F27dpKxyxcuBAODg7SolarjVojERHVDdUOwOXLl+Pjjz9GdnY2tm3bhuzsbKxevRqnTp3C2rVr0bp1a7027OzsDHNzc2RlZem0Z2Vlwc3NrcIx7u7u8Pb2hrm5udTWunVrZGZmlrslW5mpU6ciJydHWnipBhERAXoE4MWLF/Haa68BAAYMGAALCwssXrwYTzzxRI02rFQq0bFjR8TFxUltWq0WcXFx8Pf3r3BMly5dcOHCBZ1DrefPn4e7uzuUSmWFY1QqFezt7XUWIiKiagfgvXv3YGNjA+CfZwKqVCrpcoiaCg8Px/r16/HVV1/h7NmzGDNmDPLz8xEWFgYAGD58OKZOnSr1HzNmDG7duoUJEybg/Pnz2Lt3LxYsWICxY8c+Uh1ERCQ/ep33/+WXX8LW1hYAUFpaiqioqHLPBdTnZtghISG4efMmZs2ahczMTPj4+CA2NlY6MebSpUvSXWcAQK1WY//+/Zg4cSKefvppeHp6YsKECZgyZYo+H4OIiKj61wF6eXlBoVBUvTKFQjo79HHF6wCJiOo2Q10HWO1v/IyMjBpvhIiI6HFjsAvhiYiI6hIGIBERyRIDkIiIZIkBSEREssQAJCIiWapRAF68eBEzZszA66+/Lj2778cff8SZM2cMWhwREZGx6B2AP//8M9q1a4fff/8dO3fuRF5eHgDgxIkTiIyMNHiBRERExqB3AEZEROCjjz7CgQMHdO6/2aNHD/z2228GLY6IiMhY9A7AU6dO4d///ne5dhcXF2RnZxukKCIiImPTOwAdHR1x/fr1cu3Hjx+Hp6enQYoiIiIyNr0DcPDgwZgyZQoyMzOhUCig1WoRHx+PSZMmYfjw4caokYiIyOD0DsAFCxagVatWUKvVyMvLQ5s2bdC9e3cEBARgxowZxqiRiIjI4PR+/IFSqcT69esxc+ZMnD59Gnl5efD19UWLFi2MUR8REZFR6B2AR48eRdeuXfHkk0/iySefNEZNRERERqf3IdAePXqgSZMmmDZtGlJSUoxRExERkdHpHYDXrl3DBx98gJ9//hlt27aFj48PFi9ejCtXrhijPiIiIqPQOwCdnZ0xbtw4xMfH4+LFi3jttdfw1VdfwcvLCz169DBGjURERAb3SDfDbtKkCSIiIrBo0SK0a9cOP//8s6HqIiIiMqoaB2B8fDzeffdduLu7Y8iQIWjbti327t1ryNqIiIiMRu+zQKdOnYro6Ghcu3YNL7zwApYvX45XXnkFNjY2xqiPiIjIKPQOwF9++QUffvghBg0aBGdnZ2PUREREZHR6B2B8fLwx6iAiIqpV1QrA3bt348UXX4SlpSV2795dZd9+/foZpDAiIiJjqlYA9u/fH5mZmXBxcUH//v0r7adQKKDRaAxVGxERkdFUKwC1Wm2FfyYiIqqr9L4MYvPmzSgqKirXXlxcjM2bNxukKCIiImPTOwDDwsKQk5NTrv3u3bsICwszSFFERETGpncACiGgUCjKtV+5cgUODg4GKYqIiMjYqn0ZhK+vLxQKBRQKBXr27AkLi/8N1Wg0SE9PR+/evY1SJBERkaFVOwDLzv5MTk5GcHAwbG1tpfeUSiW8vLwwcOBAgxdIRERkDNUOwMjISACAl5cXQkJCYGVlZbSiiIiIjE3vO8GEhoYaow4iIqJaVa0AbNiwIc6fPw9nZ2c4OTlVeBJMmVu3bhmsOCIiImOpVgB+9tlnsLOzk/5cVQASERHVBdUKwPsPe44YMcJYtRAREdUava8DTEpKwqlTp6TXP/zwA/r3749p06ahuLjYoMUREREZi94BOHr0aJw/fx4AkJaWhpCQENjY2GD79u2YPHmywQskIiIyBr0D8Pz58/Dx8QEAbN++HYGBgfjmm28QFRWF7777ztD1ERERGUWNboVW9kSIgwcPok+fPgAAtVqN7Oxsw1ZHRERkJHoHYKdOnfDRRx/h66+/xs8//4yXXnoJAJCeng5XV1eDF0hERGQMegfgsmXLkJSUhHHjxmH69Olo3rw5AGDHjh0ICAgweIFERETGoPedYJ5++mmds0DLLF68GObm5gYpioiIyNj0DsAyiYmJOHv2LACgTZs26NChg8GKIiIiMja9A/DGjRsICQnBzz//DEdHRwDAnTt38PzzzyM6OhqNGjUydI1EREQGp/dvgOPHj0deXh7OnDmDW7du4datWzh9+jRyc3Px3nvvGaNGIiIig9N7DzA2NhYHDx5E69atpbY2bdpg1apV6NWrl0GLIyIiMha99wC1Wi0sLS3LtVtaWkrXBxIRET3u9A7AHj16YMKECbh27ZrUdvXqVUycOBE9e/Y0aHFERETGoncArly5Erm5ufDy8kKzZs3QrFkzNGnSBLm5uVixYoUxaiQiIjI4vX8DVKvVSEpKQlxcnHQZROvWrREUFGTw4oiIiIxFrwCMiYnB7t27UVxcjJ49e2L8+PHGqouIiMioqh2Aa9aswdixY9GiRQtYW1tj586duHjxIhYvXmzM+oiIiIyi2r8Brly5EpGRkUhNTUVycjK++uorrF692pi1ERERGU21AzAtLQ2hoaHS6yFDhqC0tBTXr183SmFERETGVO0ALCoqQoMGDf430MwMSqUS9+7dM0phRERExqTXSTAzZ86EjY2N9Lq4uBjz58+Hg4OD1LZ06VLDVUdERGQk1Q7A7t27IzU1VactICAAaWlp0muFQmG4yoiIiIyo2gF4+PBhI5ZBRERUu/S+EwwREVF9wAAkIiJZYgASEZEsPRYBuGrVKnh5ecHKygp+fn44duxYtcZFR0dDoVCgf//+xi2QiIjqHZMHYExMDMLDwxEZGYmkpCS0b98ewcHBuHHjRpXjMjIyMGnSJHTr1q2WKiUiovqkRgF45MgRvPHGG/D398fVq1cBAF9//TWOHj2q97qWLl2KkSNHIiwsDG3atMHatWthY2ODjRs3VjpGo9Fg6NChmDNnDpo2bVqTj0BERDKndwB+9913CA4OhrW1NY4fP46ioiIAQE5ODhYsWKDXuoqLi5GYmKjzKCUzMzMEBQUhISGh0nFz586Fi4sL3nrrrYduo6ioCLm5uToLERGR3gH40UcfYe3atVi/fj0sLS2l9i5duiApKUmvdWVnZ0Oj0cDV1VWn3dXVFZmZmRWOOXr0KDZs2ID169dXaxsLFy6Eg4ODtKjVar1qJCKi+knvAExNTUX37t3LtTs4OODOnTuGqKlSd+/exbBhw7B+/Xo4OztXa8zUqVORk5MjLZcvXzZqjUREVDfo/UR4Nzc3XLhwAV5eXjrtR48e1fv3OGdnZ5ibmyMrK0unPSsrC25ubuX6X7x4ERkZGejbt6/UptVqAQAWFhZITU1Fs2bNdMaoVCqoVCq96iIiovpP7z3AkSNHYsKECfj999+hUChw7do1bN26FZMmTcKYMWP0WpdSqUTHjh0RFxcntWm1WsTFxcHf379c/1atWuHUqVNITk6Wln79+uH5559HcnIyD28SEVG16b0HGBERAa1Wi549e6KgoADdu3eHSqXCpEmTMH78eL0LCA8PR2hoKDp16oTOnTtj2bJlyM/PR1hYGABg+PDh8PT0xMKFC2FlZYW2bdvqjHd0dASAcu1ERERV0TsAFQoFpk+fjg8//BAXLlxAXl4e2rRpA1tb2xoVEBISgps3b2LWrFnIzMyEj48PYmNjpRNjLl26BDMzk1+uSERE9YxCCCFMXURtys3NhYODA3JycmBhZYM2s/YDAFLmBsNGqfe/B4iIqJbd/z1ub29f4/Xo/Y3//PPPV/ncv59++qnGxRAREdUWvQPQx8dH53VJSQmSk5Nx+vRphIaGGqouIiIio9I7AD/77LMK22fPno28vLxHLoiIiKg2GOzskjfeeKPK+3cSERE9TgwWgAkJCbCysjLU6oiIiIxK70OgAwYM0HkthMD169fx559/YubMmQYrjIiIyJj0DkAHBwed12ZmZmjZsiXmzp2LXr16GawwIiIiY9IrADUaDcLCwtCuXTs4OTkZqyYiIiKj0+s3QHNzc/Tq1cvoT30gIiIyNr1Pgmnbti3S0tKMUQsREVGtqdEDcSdNmoQ9e/bg+vXrfNo6ERHVSdX+DXDu3Ln44IMP0KdPHwBAv379dG6JJoSAQqGARqMxfJVEREQGVu0AnDNnDt555x0cOnTImPUQERHVimoHYNlDIwIDA41WDBERUW3R6zfAqp4CQUREVJfodR2gt7f3Q0Pw1q1bj1QQERFRbdArAOfMmVPuTjBERER1kV4BOHjwYLi4uBirFiIiolpT7d8A+fsfERHVJ9UOwLKzQImIiOqDah8C1Wq1xqyDiIioVhnsgbhERER1CQOQiIhkiQFIRESyxAAkIiJZYgASEZEsMQCJiEiWGIBERCRLDEAiIpIlBiAREckSA5CIiGSJAUhERLLEACQiIlliABIRkSwxAImISJYYgEREJEsMQCIikiUGIBERyRIDkIiIZIkBSEREssQAJCIiWWIAEhGRLDEAiYhIlhiAREQkSwxAIiKSJQYgERHJEgOQiIhkiQFIRESyxAAkIiJZYgASEZEsMQCJiEiWGIBERCRLDEAiIpIlBiAREckSA5CIiGSJAUhERLLEACQiIlliABIRkSwxAImISJYYgEREJEsMQCIikqXHIgBXrVoFLy8vWFlZwc/PD8eOHau07/r169GtWzc4OTnByckJQUFBVfYnIiKqiMkDMCYmBuHh4YiMjERSUhLat2+P4OBg3Lhxo8L+hw8fxuuvv45Dhw4hISEBarUavXr1wtWrV2u5ciIiqssUQghhygL8/PzwzDPPYOXKlQAArVYLtVqN8ePHIyIi4qHjNRoNnJycsHLlSgwfPvyh/XNzc+Hg4ICcnBxYWNmgzaz9AICUucGwUVo82ochIiKju/973N7evsbrMekeYHFxMRITExEUFCS1mZmZISgoCAkJCdVaR0FBAUpKStCwYUNjlUlERPWQSXd5srOzodFo4OrqqtPu6uqKc+fOVWsdU6ZMgYeHh06I3q+oqAhFRUXS69zc3JoXTERE9YbJfwN8FIsWLUJ0dDR27doFKyurCvssXLgQDg4O0qJWq2u5SiIiehyZNACdnZ1hbm6OrKwsnfasrCy4ublVOXbJkiVYtGgR/vvf/+Lpp5+utN/UqVORk5MjLZcvXzZI7UREVLeZNACVSiU6duyIuLg4qU2r1SIuLg7+/v6Vjvvkk08wb948xMbGolOnTlVuQ6VSwd7eXmchIiIy+WmP4eHhCA0NRadOndC5c2csW7YM+fn5CAsLAwAMHz4cnp6eWLhwIQDg448/xqxZs/DNN9/Ay8sLmZmZAABbW1vY2tqa7HMQEVHdYvIADAkJwc2bNzFr1ixkZmbCx8cHsbGx0okxly5dgpnZ/3ZU16xZg+LiYrz66qs664mMjMTs2bNrs3QiIqrDTH4dYG3jdYBERHVbvbgOkIiIyFQYgEREJEsMQCIikiUGIBERyRIDkIiIZIkBSEREssQAJCIiWWIAEhGRLDEAiYhIlhiAREQkSwxAIiKSJQYgERHJEgOQiIhkiQFIRESyxAAkIiJZYgASEZEsMQCJiEiWGIBERCRLDEAiIpIlBiAREckSA5CIiGSJAUhERLLEACQiIlliABIRkSwxAImISJYYgEREJEsMQCIikiUGIBERyRIDkIiIZIkBSEREssQAJCIiWWIAEhGRLDEAiYhIlhiAREQkSwxAIiKSJQYgERHJEgOQiIhkycLUBRDVZxqNBiUlJaYug6hOMTc3h4WFBRQKhVG3wwAkMpK8vDxcuXIFQghTl0JU59jY2MDd3R1KpdJo22AAEhmBRqPBlStXYGNjg0aNGhn9X7JE9YUQAsXFxbh58ybS09PRokULmJkZ59c6BiCREZSUlEAIgUaNGsHa2trU5RDVKdbW1rC0tMTff/+N4uJiWFlZGWU7PAmGyIi450dUM8ba69PZhtG3QERE9BhiABIRkSwxAIlIbwqFAt9//73Rt3P48GEoFArcuXNHavv+++/RvHlzmJub4/3330dUVBQcHR2NVkNqairc3Nxw9+5do21Dbp599ll89913pi6DAUhEujIzMzF+/Hg0bdoUKpUKarUaffv2RVxcXK3XEhAQgOvXr8PBwUFqGz16NF599VVcvnwZ8+bNQ0hICM6fP2+0GqZOnYrx48fDzs6u3HutWrWCSqVCZmZmufe8vLywbNmycu2zZ8+Gj4+PTpsp5vzMmTMYOHAgvLy8oFAoKqy1IidPnkS3bt1gZWUFtVqNTz75pFyf7du3o1WrVrCyskK7du2wb98+nfdnzJiBiIgIaLVaQ3yUGmMAEpEkIyMDHTt2xE8//YTFixfj1KlTiI2NxfPPP4+xY8fWej1KpRJubm7SyUR5eXm4ceMGgoOD4eHhATs7O1hbW8PFxeWRtlPZzQouXbqEPXv2YMSIEeXeO3r0KO7du4dXX30VX331VY23bao5LygoQNOmTbFo0SK4ublVa0xubi569eqFxo0bIzExEYsXL8bs2bOxbt06qc+vv/6K119/HW+99RaOHz+O/v37o3///jh9+rTU58UXX8Tdu3fx448/Gvxz6UXITE5OjgAgcnJyRH5RiWg8ZY9oPGWPyC8qMXVpVI/cu3dPpKSkiHv37gkhhNBqtSK/qMQki1arrXbdL774ovD09BR5eXnl3rt9+7b0ZwBi165d0uvJkyeLFi1aCGtra9GkSRMxY8YMUVxcLL2fnJwsnnvuOWFrayvs7OxEhw4dxB9//CGEECIjI0O8/PLLwtHRUdjY2Ig2bdqIvXv3CiGEOHTokAAgbt++Lf35/uXQoUNi06ZNwsHBQafW77//Xvj6+gqVSiWaNGkiZs+eLUpK/vd3HIBYvXq16Nu3r7CxsRGRkZEVzsfixYtFp06dKnxvxIgRIiIiQvz444/C29u73PuNGzcWn332Wbn2yMhI0b59e+l1defcmCqr9UGrV68WTk5OoqioSGqbMmWKaNmypfR60KBB4qWXXtIZ5+fnJ0aPHq3TFhYWJt54441Kt/Xg36H73f89/ih4HSBRLbhXokGbWftNsu2UucGwUT78r/qtW7cQGxuL+fPno0GDBuXer+p3Njs7O0RFRcHDwwOnTp3CyJEjYWdnh8mTJwMAhg4dCl9fX6xZswbm5uZITk6GpaUlAGDs2LEoLi7GL7/8ggYNGiAlJQW2trblthEQEIDU1FS0bNkS3333HQICAtCwYUNkZGTo9Dty5AiGDx+Ozz//HN26dcPFixcxatQoAEBkZKTUb/bs2Vi0aBGWLVsGC4uK5+fIkSPo1KlTufa7d+9i+/bt+P3339GqVSvk5OTgyJEj6NatW6VzVJFHmfOtW7di9OjRVa7/xx9/1LumqiQkJKB79+46d2cJDg7Gxx9/jNu3b8PJyQkJCQkIDw/XGRccHFzuN+POnTtj0aJFBqutJhiARAQAuHDhAoQQaNWqld5jZ8yYIf3Zy8sLkyZNQnR0tBSAly5dwocffiitu0WLFlL/S5cuYeDAgWjXrh0AoGnTphVuQ6lUSoc6GzZsWOlhuzlz5iAiIgKhoaHS+ubNm4fJkyfrBOCQIUMQFhZW5ef6+++/KwzA6OhotGjRAk899RQAYPDgwdiwYYPeYfMoc96vXz/4+flV2cfT01Pv9VYlMzMTTZo00WlzdXWV3nNyckJmZqbUdn+fB38n9fDwwOXLl6HVamvlmr+KMACJaoG1pTlS5gabbNvVIR7hnqUxMTH4/PPPcfHiReTl5aG0tBT29vbS++Hh4Xj77bfx9ddfIygoCK+99hqaNWsGAHjvvfcwZswY/Pe//0VQUBAGDhyIp59+usa1nDhxAvHx8Zg/f77UptFoUFhYiIKCAtjY2ABAhcH2oHv37lV4F5KNGzfijTfekF6/8cYbCAwMxIoVKyo8WaYyjzLndnZ2em3rcWNtbQ2tVouioiKT3S2JJ8EQ1QKFQgEbpYVJlurejaZFixZQKBQ4d+6cXp8tISEBQ4cORZ8+fbBnzx4cP34c06dPR3FxsdRn9uzZOHPmDF566SX89NNPaNOmDXbt2gUAePvtt5GWloZhw4bh1KlT6NSpE1asWKFXDffLy8vDnDlzkJycLC2nTp3CX3/9pRNmFR1yfJCzszNu376t05aSkoLffvsNkydPhoWFBSwsLPDss8+ioKAA0dHRUj97e3vk5OSUW+edO3eks1prOufAP4dAbW1tq1yOHDmi93qr4ubmhqysLJ22stdle+SV9Xlwj/3WrVto0KCBSW8VyAAkIgD/HFYMDg7GqlWrkJ+fX+79+6/Fu9+vv/6Kxo0bY/r06ejUqRNatGiBv//+u1w/b29vTJw4Ef/9738xYMAAbNq0SXpPrVbjnXfewc6dO/HBBx9g/fr1Nf4cHTp0QGpqKpo3b15u0fdQm6+vL1JSUnTaNmzYgO7du+PEiRM6IRseHo4NGzZI/Vq2bInExMRy60xKSoK3tzeAms858M8h0Pu3X9FSnb1cffj7++OXX37ROWv2wIEDaNmyJZycnKQ+D16+ceDAAfj7++u0nT59Gr6+vgatT2+PdApNHcSzQKk2VHUG2+Ps4sWLws3NTbRp00bs2LFDnD9/XqSkpIjly5eLVq1aSf1w31mgP/zwg7CwsBDffvutuHDhgli+fLlo2LChdGZmQUGBGDt2rDh06JDIyMgQR48eFc2aNROTJ08WQggxYcIEERsbK9LS0kRiYqLw8/MTgwYNEkLongUqxD9nReL/n/1Z5sGzQGNjY4WFhYWYPXu2OH36tEhJSRHffvutmD59eoX1V2X37t3CxcVFlJaWCiGEKC4uFo0aNRJr1qwp1zclJUUAEKdPnxZCCBEfHy/MzMzERx99JFJSUsSpU6fEtGnThIWFhTh16pTec25oRUVF4vjx4+L48ePC3d1dTJo0SRw/flz89ddfUp8VK1aIHj16SK/v3LkjXF1dxbBhw8Tp06dFdHS0sLGxEV988YXUJz4+XlhYWIglS5aIs2fPisjISGFpaanzmYUQIjAwUMydO7fS+mrjLFAGIAOQjKCuBqAQQly7dk2MHTtWNG7cWCiVSuHp6Sn69eunEzoPBsiHH34o/vWvfwlbW1sREhIiPvvsMymUioqKxODBg4VarRZKpVJ4eHiIcePGSXMzbtw40axZM6FSqUSjRo3EsGHDRHZ2thCiZgEoxD8hGBAQIKytrYW9vb3o3LmzWLduXaX1V6akpER4eHiI2NhYIYQQO3bsEGZmZiIzM7PC/q1btxYTJ06UXu/fv1906dJFODk5iX/961/iueeeEz///HO5cdWZc0NLT08vd1kJABEYGCj1iYyMFI0bN9YZd+LECdG1a1ehUqmEp6enWLRoUbl1b9u2TXh7ewulUimeeuop6bKWMleuXBGWlpbi8uXLldZXGwGoEEJeT+vMzc2Fg4MDcnJyYGFlI52aXt1TxYmqo7CwEOnp6WjSpInRHuVCtWPVqlXYvXs39u83zWUs9dGUKVNw+/ZtnQvoH1TV36H7v8fvP9lKX/zGJyKqwujRo3Hnzh3cvXu3Tp91+ThxcXEpd62gKTAAiYiqYGFhgenTp5u6jHrlgw8+MHUJAHgWKBERyRQDkIiIZIkBSGREMjvHjMhgauPvDgOQyAjMzf+5/dj9d0MhouorKCgAAOmm6cbwWJwEs2rVKixevBiZmZlo3749VqxYgc6dO1faf/v27Zg5cyYyMjLQokULfPzxx+jTp08tVkxUNQsLC9jY2ODmzZuwtLQ02c1+ieoaIQQKCgpw48YNODo6Sv+YNAaTB2BMTAzCw8Oxdu1a+Pn5YdmyZQgODkZqamqFD7kse9jiwoUL8fLLL+Obb75B//79kZSUhLZt25rgExCVp1Ao4O7ujvT09ApvC0ZEVXN0dKz2g3pryuQXwvv5+eGZZ57BypUrAQBarRZqtRrjx49HREREuf4hISHIz8/Hnj17pLZnn30WPj4+WLt27UO3xwvhqTZptVoeBiXSk6WlZZV7fvXiQvji4mIkJiZi6tSpUpuZmRmCgoKQkJBQ4ZjqPmyxTFFREYqKiqTXubm5j144UTWZmZnxTjBEjymT/jCRnZ0NjUZTrYcnlqnuwxbLLFy4EA4ODtKiVqsNUzwREdVp9f6X+alTpyInJ0daLl++LL1X9pDSlLnB1X5oKBER1Q8mPQTq7OwMc3Pzaj08sUx1H7ZYRqVSQaVSVfhe2UNKiYhIfkz67a9UKtGxY0fExcWhf//+AP45aSAuLg7jxo2rcEzZwxbff/99qa2ihy1WpuycH/4WSERUN5V9fz/yOZyP9DAlA4iOjhYqlUpERUWJlJQUMWrUKOHo6Cg9b2vYsGEiIiJC6l/dhy1W5vLlyxU+A4sLFy5cuNStparnCVaHyY//hYSE4ObNm5g1axYyMzPh4+OD2NhY6USXS5cu6VxEHBAQgG+++QYzZszAtGnT0KJFC3z//ffVvgbQw8MDly9fhp2dHRQKBXJzc6FWq3H58uVHOp22vuL8PBznqGqcn4fjHFXtwfkRQuDu3bvw8PB4pPWa/DpAUzPU9ST1Fefn4ThHVeP8PBznqGrGmp96fxYoERFRRRiAREQkS7IPQJVKhcjIyEovlZA7zs/DcY6qxvl5OM5R1Yw1P7L/DZCIiORJ9nuAREQkTwxAIiKSJQYgERHJEgOQiIhkSRYBuGrVKnh5ecHKygp+fn44duxYlf23b9+OVq1awcrKCu3atcO+fftqqVLT0Gd+1q9fj27dusHJyQlOTk4ICgp66HzWB/r+N1QmOjoaCoVCutdtfaXv/Ny5cwdjx46Fu7s7VCoVvL29+ffsAcuWLUPLli1hbW0NtVqNiRMnorCwsJaqrV2//PIL+vbtCw8PDygUikqf73q/w4cPo0OHDlCpVGjevDmioqL03/Aj3UitDoiOjhZKpVJs3LhRnDlzRowcOVI4OjqKrKysCvvHx8cLc3Nz8cknn4iUlBQxY8YMve41WtfoOz9DhgwRq1atEsePHxdnz54VI0aMEA4ODuLKlSu1XHnt0XeOyqSnpwtPT0/RrVs38corr9ROsSag7/wUFRWJTp06iT59+oijR4+K9PR0cfjwYZGcnFzLldcefedo69atQqVSia1bt4r09HSxf/9+4e7uLiZOnFjLldeOffv2ienTp4udO3cKAGLXrl1V9k9LSxM2NjYiPDxcpKSkiBUrVghzc3MRGxur13brfQB27txZjB07Vnqt0WiEh4eHWLhwYYX9Bw0aJF566SWdNj8/PzF69Gij1mkq+s7Pg0pLS4WdnZ346quvjFWiydVkjkpLS0VAQID48ssvRWhoaL0OQH3nZ82aNaJp06aiuLi4tko0OX3naOzYsaJHjx46beHh4aJLly5GrfNxUJ0AnDx5snjqqad02kJCQkRwcLBe26rXh0CLi4uRmJiIoKAgqc3MzAxBQUFISEiocExCQoJOfwAIDg6utH9dVpP5eVBBQQFKSkrQsGFDY5VpUjWdo7lz58LFxQVvvfVWbZRpMjWZn927d8Pf3x9jx46Fq6sr2rZtiwULFkCj0dRW2bWqJnMUEBCAxMRE6TBpWloa9u3bhz59+tRKzY87Q31Pm/xpEMaUnZ0NjUYjPVmijKurK86dO1fhmMzMzAr7Z2ZmGq1OU6nJ/DxoypQp8PDwKPcfY31Rkzk6evQoNmzYgOTk5Fqo0LRqMj9paWn46aefMHToUOzbtw8XLlzAu+++i5KSEkRGRtZG2bWqJnM0ZMgQZGdno2vXrhBCoLS0FO+88w6mTZtWGyU/9ir7ns7NzcW9e/dgbW1drfXU6z1AMq5FixYhOjoau3btgpWVlanLeSzcvXsXw4YNw/r16+Hs7Gzqch5LWq0WLi4uWLduHTp27IiQkBBMnz4da9euNXVpj43Dhw9jwYIFWL16NZKSkrBz507s3bsX8+bNM3Vp9Uq93gN0dnaGubk5srKydNqzsrLg5uZW4Rg3Nze9+tdlNZmfMkuWLMGiRYtw8OBBPP3008Ys06T0naOLFy8iIyMDffv2ldq0Wi0AwMLCAqmpqWjWrJlxi65FNflvyN3dHZaWljA3N5faWrdujczMTBQXF0OpVBq15tpWkzmaOXMmhg0bhrfffhsA0K5dO+Tn52PUqFGYPn26zjNS5aiy72l7e/tq7/0B9XwPUKlUomPHjoiLi5PatFot4uLi4O/vX+EYf39/nf4AcODAgUr712U1mR8A+OSTTzBv3jzExsaiU6dOtVGqyeg7R61atcKpU6eQnJwsLf369cPzzz+P5ORkqNXq2izf6Gry31CXLl1w4cIF6R8GAHD+/Hm4u7vXu/ADajZHBQUF5UKu7B8MgrdvNtz3tH7n59Q90dHRQqVSiaioKJGSkiJGjRolHB0dRWZmphBCiGHDhomIiAipf3x8vLCwsBBLliwRZ8+eFZGRkfX+Mgh95mfRokVCqVSKHTt2iOvXr0vL3bt3TfURjE7fOXpQfT8LVN/5uXTpkrCzsxPjxo0TqampYs+ePcLFxUV89NFHpvoIRqfvHEVGRgo7Ozvx7bffirS0NPHf//5XNGvWTAwaNMhUH8Go7t69K44fPy6OHz8uAIilS5eK48ePi7///lsIIURERIQYNmyY1L/sMogPP/xQnD17VqxatYqXQVRmxYoV4sknnxRKpVJ07txZ/Pbbb9J7gYGBIjQ0VKf/tm3bhLe3t1AqleKpp54Se/fureWKa5c+89O4cWMBoNwSGRlZ+4XXIn3/G7pffQ9AIfSfn19//VX4+fkJlUolmjZtKubPny9KS0truerapc8clZSUiNmzZ4tmzZoJKysroVarxbvvvitu375d+4XXgkOHDlX4vVI2J6GhoSIwMLDcGB8fH6FUKkXTpk3Fpk2b9N4uH4dERESyVK9/AyQiIqoMA5CIiGSJAUhERLLEACQiIlliABIRkSwxAImISJYYgEREJEsMQKIKREVFwdHR0dRl1Fh1nqo9YsSIev+keqKqMACp3hoxYgQUCkW55cKFC6YuDVFRUVI9ZmZmeOKJJxAWFoYbN24YZP3Xr1/Hiy++CADIyMiAQqEo93im5cuXIyoqyiDbq8zs2bOlz2lubg61Wo1Ro0bh1q1beq2HYU3GUK+fBkHUu3dvbNq0SaetUaNGJqpGl729PVJTU6HVanHixAmEhYXh2rVr2L9//yOvuzpPL3FwcHjk7VTHU089hYMHD0Kj0eDs2bN48803kZOTg5iYmFrZPlFluAdI9ZpKpYKbm5vOYm5ujqVLl6Jdu3Zo0KAB1Go13n33XeTl5VW6nhMnTuD555+HnZ0d7O3t0bFjR/z555/S+0ePHkW3bt1gbW0NtVqN9957D/n5+VXWplAo4ObmBg8PD7z44ot47733cPDgQdy7dw9arRZz587FE088AZVKBR8fH8TGxkpji4uLMW7cOLi7u8PKygqNGzfGwoULddZddgi0SZMmAABfX18oFAo899xzAHT3qtatWwcPDw+dJzQAwCuvvII333xTev3DDz+gQ4cOsLKyQtOmTTFnzhyUlpZW+TktLCzg5uYGT09PBAUF4bXXXsOBAwek9zUaDd566y00adIE1tbWaNmyJZYvXy69P3v2bHz11Vf44YcfpL3Jw4cPAwAuX76MQYMGwdHREQ0bNsQrr7yCjIyMKushKsMAJFkyMzPD559/jjNnzuCrr77CTz/9hMmTJ1faf+jQoXjiiSfwxx9/IDExEREREbC0tATwzzMAe/fujYEDB+LkyZOIiYnB0aNHMW7cOL1qsra2hlarRWlpKZYvX45PP/0US5YswcmTJxEcHIx+/frhr7/+AgB8/vnn2L17N7Zt24bU1FRs3boVXl5eFa732LFjAICDBw/i+vXr2LlzZ7k+r732Gv7v//4Phw4dktpu3bqF2NhYDB06FABw5MgRDB8+HBMmTEBKSgq++OILREVFYf78+dX+jBkZGdi/f7/OY4+0Wi2eeOIJbN++HSkpKZg1axamTZuGbdu2AQAmTZqEQYMGoXfv3rh+/TquX7+OgIAAlJSUIDg4GHZ2djhy5Aji4+Nha2uL3r17o7i4uNo1kYw96l28iR5XoaGhwtzcXDRo0EBaXn311Qr7bt++XfzrX/+SXm/atEk4ODhIr+3s7ERUVFSFY9966y0xatQonbYjR44IMzMzce/evQrHPLj+8+fPC29vb9GpUychhBAeHh5i/vz5OmOeeeYZ8e677wohhBg/frzo0aOH0Gq1Fa4fgNi1a5cQQoj09HQBQBw/flynz4NPqXjllVfEm2++Kb3+4osvhIeHh9BoNEIIIXr27CkWLFigs46vv/5auLu7V1iDEP881sfMzEw0aNBAWFlZSXf5X7p0aaVjhBBi7NixYuDAgZXWWrbtli1b6sxBUVGRsLa2Fvv3769y/URCCMHfAKlee/7557FmzRrpdYMGDQD8sze0cOFCnDt3Drm5uSgtLUVhYSEKCgpgY2NTbj3h4eF4++238fXXX0uH8cqe7H7ixAmcPHkSW7dulfoLIaDVapGeno7WrVtXWFtOTg5sbW2h1WpRWFiIrl274ssvv0Rubi6uXbuGLl266PTv0qULTpw4AeCfw5cvvPACWrZsid69e+Pll19Gr169Hmmuhg4dipEjR2L16tVQqVTYunUrBg8eLD2Y9cSJE4iPj9fZ49NoNFXOGwC0bNkSu3fvRmFhIbZs2YLk5GSMHz9ep8+qVauwceNGXLp0Cffu3UNxcTF8fHyqrPfEiRO4cOEC7OzsdNoLCwtx8eLFGswAyQ0DkOq1Bg0aoHnz5jptGRkZePnllzFmzBjMnz8fDRs2xNGjR/HWW2+huLi4wi/y2bNnY8iQIdi7dy9+/PFHREZGIjo6Gv/+97+Rl5eH0aNH47333is37sknn6y0Njs7OyQlJcHMzAzu7u6wtrYGAOTm5j70c3Xo0AHp6en48ccfcfDgQQwaNAhBQUHYsWPHQ8dWpm/fvhBCYO/evXjmmWdw5MgRfPbZZ9L7eXl5mDNnDgYMGFBurJWVVaXrVSqV0v8HixYtwksvvYQ5c+Zg3rx5AIDo6GhMmjQJn376Kfz9/WFnZ4fFixfj999/r7LevLw8dOzYUecfHmUelxOd6PHGACTZSUxMhFarxaeffirt3ZT93lQVb29veHt7Y+LEiXj99dexadMm/Pvf/0aHDh2QkpJSLmgfxszMrMIx9vb28PDwQHx8PAIDA6X2+Ph4dO7cWadfSEgIQkJC8Oqrr6J37964desWGjZsqLO+st/bNBpNlfVYWVlhwIAB2Lp1Ky5cuICWLVuiQ4cO0vsdOnRAamqq3p/zQTNmzECPHj0wZswY6XMGBATg3Xfflfo8uAenVCrL1d+hQwfExMTAxcUF9vb2j1QTyRNPgiHZad68OUpKSrBixQqkpaXh66+/xtq1ayvtf+/ePYwbNw6HDx/G33//jfj4ePzxxx/Soc0pU6bg119/xbhx45CcnIy//voLP/zwg94nwdzvww8/xMcff4yYmBikpqYiIiICycnJmDBhAgBg6dKl+Pbbb3Hu3DmcP38e27dvh5ubW4UX77u4uMDa2hqxsbHIyspCTk5OpdsdOnQo9u7di40bN0onv5SZNWsWNm/ejDlz5uDMmTM4e/YsoqOjMWPGDL0+m7+/P55++mksWLAAANCiRQv8+eef2L9/P86fP4+ZM2fijz/+0Bnj5eWFkydPIjU1FdnZ2SgpKcHQoUPh7OyMV155BUeOHEF6ejoOHz6M9957D1euXNGrJpIpU/8ISWQsFZ04UWbp0qXC3d1dWFtbi+DgYLF582YBQNy+fVsIoXuSSlFRkRg8eLBQq9VCqVQKDw8PMW7cOJ0TXI4dOyZeeOEFYWtrKxo0aCCefvrpciex3O/Bk2AepNFoxOzZs4Wnp6ewtLQU7du3Fz/++KP0/rp164SPj49o0KCBsLe3Fz179hRJSUnS+7jvJBghhFi/fr1Qq9XCzMxMBAYGVjo/Go1GuLu7CwDi4sWL5eqKjY0VAQEBwtraWtjb24vOnTuLdevWVfo5IiMjRfv27cu1f/vtt0KlUolLly6JwsJCMWLECOHg4CAcHR3FmDFjREREhM64GzduSPMLQBw6dEgIIcT169fF8OHDhbOzs1CpVKJp06Zi5MiRIicnp9KaiMoohBDCtBFMRERU+3gIlIiIZIkBSEREssQAJCIiWWIAEhGRLDEAiYhIlhiAREQkSwxAIiKSJQYgERHJEgOQiIhkiQFIRESyxAAkIiJZYgASEZEs/T8IAEPRl63tpAAAAABJRU5ErkJggg==\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Demostrate logistic regression model for breast cancer\n",
        "import numpy as np\n",
        "import pandas as pd\n",
        "import matplotlib.pyplot as plt\n",
        "import seaborn as sns\n",
        "from sklearn.model_selection import train_test_split\n",
        "from sklearn.linear_model import LogisticRegression\n",
        "from sklearn.metrics import accuracy_score,confusion_matrix,classification_report,recall_score,f1_score,precision_score,roc_auc_score,precision_recall_curve\n",
        "from sklearn.datasets import load_breast_cancer\n",
        "\n",
        "# Load the breast cancer dataset\n",
        "data = load_breast_cancer()\n",
        "df_cancer = pd.DataFrame(data.data, columns=data.feature_names)\n",
        "df_cancer['target'] = data.target"
      ],
      "metadata": {
        "id": "X1WyM3-cEehi"
      },
      "execution_count": 311,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "cancer_model = LogisticRegression(max_iter=5000)\n",
        "cancer_model.fit(x_train, y_train)"
      ],
      "metadata": {
        "id": "3gM535H5E-uW",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 80
        },
        "outputId": "1908f6b0-5d57-43c7-aa91-5a790aefd43e"
      },
      "execution_count": 312,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "LogisticRegression(max_iter=5000)"
            ],
            "text/html": [
              "<style>#sk-container-id-15 {\n",
              "  /* Definition of color scheme common for light and dark mode */\n",
              "  --sklearn-color-text: #000;\n",
              "  --sklearn-color-text-muted: #666;\n",
              "  --sklearn-color-line: gray;\n",
              "  /* Definition of color scheme for unfitted estimators */\n",
              "  --sklearn-color-unfitted-level-0: #fff5e6;\n",
              "  --sklearn-color-unfitted-level-1: #f6e4d2;\n",
              "  --sklearn-color-unfitted-level-2: #ffe0b3;\n",
              "  --sklearn-color-unfitted-level-3: chocolate;\n",
              "  /* Definition of color scheme for fitted estimators */\n",
              "  --sklearn-color-fitted-level-0: #f0f8ff;\n",
              "  --sklearn-color-fitted-level-1: #d4ebff;\n",
              "  --sklearn-color-fitted-level-2: #b3dbfd;\n",
              "  --sklearn-color-fitted-level-3: cornflowerblue;\n",
              "\n",
              "  /* Specific color for light theme */\n",
              "  --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));\n",
              "  --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, white)));\n",
              "  --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));\n",
              "  --sklearn-color-icon: #696969;\n",
              "\n",
              "  @media (prefers-color-scheme: dark) {\n",
              "    /* Redefinition of color scheme for dark theme */\n",
              "    --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));\n",
              "    --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, #111)));\n",
              "    --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));\n",
              "    --sklearn-color-icon: #878787;\n",
              "  }\n",
              "}\n",
              "\n",
              "#sk-container-id-15 {\n",
              "  color: var(--sklearn-color-text);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 pre {\n",
              "  padding: 0;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 input.sk-hidden--visually {\n",
              "  border: 0;\n",
              "  clip: rect(1px 1px 1px 1px);\n",
              "  clip: rect(1px, 1px, 1px, 1px);\n",
              "  height: 1px;\n",
              "  margin: -1px;\n",
              "  overflow: hidden;\n",
              "  padding: 0;\n",
              "  position: absolute;\n",
              "  width: 1px;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-dashed-wrapped {\n",
              "  border: 1px dashed var(--sklearn-color-line);\n",
              "  margin: 0 0.4em 0.5em 0.4em;\n",
              "  box-sizing: border-box;\n",
              "  padding-bottom: 0.4em;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-container {\n",
              "  /* jupyter's `normalize.less` sets `[hidden] { display: none; }`\n",
              "     but bootstrap.min.css set `[hidden] { display: none !important; }`\n",
              "     so we also need the `!important` here to be able to override the\n",
              "     default hidden behavior on the sphinx rendered scikit-learn.org.\n",
              "     See: https://github.com/scikit-learn/scikit-learn/issues/21755 */\n",
              "  display: inline-block !important;\n",
              "  position: relative;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-text-repr-fallback {\n",
              "  display: none;\n",
              "}\n",
              "\n",
              "div.sk-parallel-item,\n",
              "div.sk-serial,\n",
              "div.sk-item {\n",
              "  /* draw centered vertical line to link estimators */\n",
              "  background-image: linear-gradient(var(--sklearn-color-text-on-default-background), var(--sklearn-color-text-on-default-background));\n",
              "  background-size: 2px 100%;\n",
              "  background-repeat: no-repeat;\n",
              "  background-position: center center;\n",
              "}\n",
              "\n",
              "/* Parallel-specific style estimator block */\n",
              "\n",
              "#sk-container-id-15 div.sk-parallel-item::after {\n",
              "  content: \"\";\n",
              "  width: 100%;\n",
              "  border-bottom: 2px solid var(--sklearn-color-text-on-default-background);\n",
              "  flex-grow: 1;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-parallel {\n",
              "  display: flex;\n",
              "  align-items: stretch;\n",
              "  justify-content: center;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  position: relative;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-parallel-item {\n",
              "  display: flex;\n",
              "  flex-direction: column;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-parallel-item:first-child::after {\n",
              "  align-self: flex-end;\n",
              "  width: 50%;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-parallel-item:last-child::after {\n",
              "  align-self: flex-start;\n",
              "  width: 50%;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-parallel-item:only-child::after {\n",
              "  width: 0;\n",
              "}\n",
              "\n",
              "/* Serial-specific style estimator block */\n",
              "\n",
              "#sk-container-id-15 div.sk-serial {\n",
              "  display: flex;\n",
              "  flex-direction: column;\n",
              "  align-items: center;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  padding-right: 1em;\n",
              "  padding-left: 1em;\n",
              "}\n",
              "\n",
              "\n",
              "/* Toggleable style: style used for estimator/Pipeline/ColumnTransformer box that is\n",
              "clickable and can be expanded/collapsed.\n",
              "- Pipeline and ColumnTransformer use this feature and define the default style\n",
              "- Estimators will overwrite some part of the style using the `sk-estimator` class\n",
              "*/\n",
              "\n",
              "/* Pipeline and ColumnTransformer style (default) */\n",
              "\n",
              "#sk-container-id-15 div.sk-toggleable {\n",
              "  /* Default theme specific background. It is overwritten whether we have a\n",
              "  specific estimator or a Pipeline/ColumnTransformer */\n",
              "  background-color: var(--sklearn-color-background);\n",
              "}\n",
              "\n",
              "/* Toggleable label */\n",
              "#sk-container-id-15 label.sk-toggleable__label {\n",
              "  cursor: pointer;\n",
              "  display: flex;\n",
              "  width: 100%;\n",
              "  margin-bottom: 0;\n",
              "  padding: 0.5em;\n",
              "  box-sizing: border-box;\n",
              "  text-align: center;\n",
              "  align-items: start;\n",
              "  justify-content: space-between;\n",
              "  gap: 0.5em;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 label.sk-toggleable__label .caption {\n",
              "  font-size: 0.6rem;\n",
              "  font-weight: lighter;\n",
              "  color: var(--sklearn-color-text-muted);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 label.sk-toggleable__label-arrow:before {\n",
              "  /* Arrow on the left of the label */\n",
              "  content: \"▸\";\n",
              "  float: left;\n",
              "  margin-right: 0.25em;\n",
              "  color: var(--sklearn-color-icon);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 label.sk-toggleable__label-arrow:hover:before {\n",
              "  color: var(--sklearn-color-text);\n",
              "}\n",
              "\n",
              "/* Toggleable content - dropdown */\n",
              "\n",
              "#sk-container-id-15 div.sk-toggleable__content {\n",
              "  max-height: 0;\n",
              "  max-width: 0;\n",
              "  overflow: hidden;\n",
              "  text-align: left;\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-toggleable__content.fitted {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-toggleable__content pre {\n",
              "  margin: 0.2em;\n",
              "  border-radius: 0.25em;\n",
              "  color: var(--sklearn-color-text);\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-toggleable__content.fitted pre {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 input.sk-toggleable__control:checked~div.sk-toggleable__content {\n",
              "  /* Expand drop-down */\n",
              "  max-height: 200px;\n",
              "  max-width: 100%;\n",
              "  overflow: auto;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 input.sk-toggleable__control:checked~label.sk-toggleable__label-arrow:before {\n",
              "  content: \"▾\";\n",
              "}\n",
              "\n",
              "/* Pipeline/ColumnTransformer-specific style */\n",
              "\n",
              "#sk-container-id-15 div.sk-label input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-label.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Estimator-specific style */\n",
              "\n",
              "/* Colorize estimator box */\n",
              "#sk-container-id-15 div.sk-estimator input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-estimator.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-label label.sk-toggleable__label,\n",
              "#sk-container-id-15 div.sk-label label {\n",
              "  /* The background is the default theme color */\n",
              "  color: var(--sklearn-color-text-on-default-background);\n",
              "}\n",
              "\n",
              "/* On hover, darken the color of the background */\n",
              "#sk-container-id-15 div.sk-label:hover label.sk-toggleable__label {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "/* Label box, darken color on hover, fitted */\n",
              "#sk-container-id-15 div.sk-label.fitted:hover label.sk-toggleable__label.fitted {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Estimator label */\n",
              "\n",
              "#sk-container-id-15 div.sk-label label {\n",
              "  font-family: monospace;\n",
              "  font-weight: bold;\n",
              "  display: inline-block;\n",
              "  line-height: 1.2em;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-label-container {\n",
              "  text-align: center;\n",
              "}\n",
              "\n",
              "/* Estimator-specific */\n",
              "#sk-container-id-15 div.sk-estimator {\n",
              "  font-family: monospace;\n",
              "  border: 1px dotted var(--sklearn-color-border-box);\n",
              "  border-radius: 0.25em;\n",
              "  box-sizing: border-box;\n",
              "  margin-bottom: 0.5em;\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-estimator.fitted {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "/* on hover */\n",
              "#sk-container-id-15 div.sk-estimator:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-15 div.sk-estimator.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Specification for estimator info (e.g. \"i\" and \"?\") */\n",
              "\n",
              "/* Common style for \"i\" and \"?\" */\n",
              "\n",
              ".sk-estimator-doc-link,\n",
              "a:link.sk-estimator-doc-link,\n",
              "a:visited.sk-estimator-doc-link {\n",
              "  float: right;\n",
              "  font-size: smaller;\n",
              "  line-height: 1em;\n",
              "  font-family: monospace;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  border-radius: 1em;\n",
              "  height: 1em;\n",
              "  width: 1em;\n",
              "  text-decoration: none !important;\n",
              "  margin-left: 0.5em;\n",
              "  text-align: center;\n",
              "  /* unfitted */\n",
              "  border: var(--sklearn-color-unfitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-unfitted-level-1);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link.fitted,\n",
              "a:link.sk-estimator-doc-link.fitted,\n",
              "a:visited.sk-estimator-doc-link.fitted {\n",
              "  /* fitted */\n",
              "  border: var(--sklearn-color-fitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-fitted-level-1);\n",
              "}\n",
              "\n",
              "/* On hover */\n",
              "div.sk-estimator:hover .sk-estimator-doc-link:hover,\n",
              ".sk-estimator-doc-link:hover,\n",
              "div.sk-label-container:hover .sk-estimator-doc-link:hover,\n",
              ".sk-estimator-doc-link:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "div.sk-estimator.fitted:hover .sk-estimator-doc-link.fitted:hover,\n",
              ".sk-estimator-doc-link.fitted:hover,\n",
              "div.sk-label-container:hover .sk-estimator-doc-link.fitted:hover,\n",
              ".sk-estimator-doc-link.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "/* Span, style for the box shown on hovering the info icon */\n",
              ".sk-estimator-doc-link span {\n",
              "  display: none;\n",
              "  z-index: 9999;\n",
              "  position: relative;\n",
              "  font-weight: normal;\n",
              "  right: .2ex;\n",
              "  padding: .5ex;\n",
              "  margin: .5ex;\n",
              "  width: min-content;\n",
              "  min-width: 20ex;\n",
              "  max-width: 50ex;\n",
              "  color: var(--sklearn-color-text);\n",
              "  box-shadow: 2pt 2pt 4pt #999;\n",
              "  /* unfitted */\n",
              "  background: var(--sklearn-color-unfitted-level-0);\n",
              "  border: .5pt solid var(--sklearn-color-unfitted-level-3);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link.fitted span {\n",
              "  /* fitted */\n",
              "  background: var(--sklearn-color-fitted-level-0);\n",
              "  border: var(--sklearn-color-fitted-level-3);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link:hover span {\n",
              "  display: block;\n",
              "}\n",
              "\n",
              "/* \"?\"-specific style due to the `<a>` HTML tag */\n",
              "\n",
              "#sk-container-id-15 a.estimator_doc_link {\n",
              "  float: right;\n",
              "  font-size: 1rem;\n",
              "  line-height: 1em;\n",
              "  font-family: monospace;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  border-radius: 1rem;\n",
              "  height: 1rem;\n",
              "  width: 1rem;\n",
              "  text-decoration: none;\n",
              "  /* unfitted */\n",
              "  color: var(--sklearn-color-unfitted-level-1);\n",
              "  border: var(--sklearn-color-unfitted-level-1) 1pt solid;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 a.estimator_doc_link.fitted {\n",
              "  /* fitted */\n",
              "  border: var(--sklearn-color-fitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-fitted-level-1);\n",
              "}\n",
              "\n",
              "/* On hover */\n",
              "#sk-container-id-15 a.estimator_doc_link:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "#sk-container-id-15 a.estimator_doc_link.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-3);\n",
              "}\n",
              "</style><div id=\"sk-container-id-15\" class=\"sk-top-container\"><div class=\"sk-text-repr-fallback\"><pre>LogisticRegression(max_iter=5000)</pre><b>In a Jupyter environment, please rerun this cell to show the HTML representation or trust the notebook. <br />On GitHub, the HTML representation is unable to render, please try loading this page with nbviewer.org.</b></div><div class=\"sk-container\" hidden><div class=\"sk-item\"><div class=\"sk-estimator fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-33\" type=\"checkbox\" checked><label for=\"sk-estimator-id-33\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>LogisticRegression</div></div><div><a class=\"sk-estimator-doc-link fitted\" rel=\"noreferrer\" target=\"_blank\" href=\"https://scikit-learn.org/1.6/modules/generated/sklearn.linear_model.LogisticRegression.html\">?<span>Documentation for LogisticRegression</span></a><span class=\"sk-estimator-doc-link fitted\">i<span>Fitted</span></span></div></label><div class=\"sk-toggleable__content fitted\"><pre>LogisticRegression(max_iter=5000)</pre></div> </div></div></div></div>"
            ]
          },
          "metadata": {},
          "execution_count": 312
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.head()"
      ],
      "metadata": {
        "id": "CT6vr6FZEwr2",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 206
        },
        "outputId": "ef35029f-1c3c-4b70-b5ab-1155eeb3cf86"
      },
      "execution_count": 313,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "   Hours  Pass\n",
              "0      1     0\n",
              "1      2     0\n",
              "2      3     0\n",
              "3      4     0\n",
              "4      5     0"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-14951e11-d137-4635-805a-7d56ce90c4ab\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>Hours</th>\n",
              "      <th>Pass</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>1</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>2</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>3</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>3</th>\n",
              "      <td>4</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>4</th>\n",
              "      <td>5</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-14951e11-d137-4635-805a-7d56ce90c4ab')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-14951e11-d137-4635-805a-7d56ce90c4ab button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-14951e11-d137-4635-805a-7d56ce90c4ab');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "variable_name": "df",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 10,\n  \"fields\": [\n    {\n      \"column\": \"Hours\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 3,\n        \"min\": 1,\n        \"max\": 10,\n        \"num_unique_values\": 10,\n        \"samples\": [\n          9,\n          2,\n          6\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Pass\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 0,\n        \"max\": 1,\n        \"num_unique_values\": 2,\n        \"samples\": [\n          1,\n          0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 313
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.tail()"
      ],
      "metadata": {
        "id": "1lSWM760E5WV",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 206
        },
        "outputId": "f5dcff64-f884-4b28-a72a-eebfb1f40867"
      },
      "execution_count": 314,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "   Hours  Pass\n",
              "5      6     0\n",
              "6      7     1\n",
              "7      8     1\n",
              "8      9     1\n",
              "9     10     1"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-5eb6d180-e4c4-486d-8f3e-d64a900fdacf\" class=\"colab-df-container\">\n",
              "    <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>Hours</th>\n",
              "      <th>Pass</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>5</th>\n",
              "      <td>6</td>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>6</th>\n",
              "      <td>7</td>\n",
              "      <td>1</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>7</th>\n",
              "      <td>8</td>\n",
              "      <td>1</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>8</th>\n",
              "      <td>9</td>\n",
              "      <td>1</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>9</th>\n",
              "      <td>10</td>\n",
              "      <td>1</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "    <div class=\"colab-df-buttons\">\n",
              "\n",
              "  <div class=\"colab-df-container\">\n",
              "    <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-5eb6d180-e4c4-486d-8f3e-d64a900fdacf')\"\n",
              "            title=\"Convert this dataframe to an interactive table.\"\n",
              "            style=\"display:none;\">\n",
              "\n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 -960 960 960\">\n",
              "    <path d=\"M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z\"/>\n",
              "  </svg>\n",
              "    </button>\n",
              "\n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    .colab-df-buttons div {\n",
              "      margin-bottom: 4px;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "    <script>\n",
              "      const buttonEl =\n",
              "        document.querySelector('#df-5eb6d180-e4c4-486d-8f3e-d64a900fdacf button.colab-df-convert');\n",
              "      buttonEl.style.display =\n",
              "        google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "      async function convertToInteractive(key) {\n",
              "        const element = document.querySelector('#df-5eb6d180-e4c4-486d-8f3e-d64a900fdacf');\n",
              "        const dataTable =\n",
              "          await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                    [key], {});\n",
              "        if (!dataTable) return;\n",
              "\n",
              "        const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "          '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "          + ' to learn more about interactive tables.';\n",
              "        element.innerHTML = '';\n",
              "        dataTable['output_type'] = 'display_data';\n",
              "        await google.colab.output.renderOutput(dataTable, element);\n",
              "        const docLink = document.createElement('div');\n",
              "        docLink.innerHTML = docLinkHtml;\n",
              "        element.appendChild(docLink);\n",
              "      }\n",
              "    </script>\n",
              "  </div>\n",
              "\n",
              "\n",
              "    </div>\n",
              "  </div>\n"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "dataframe",
              "summary": "{\n  \"name\": \"df\",\n  \"rows\": 5,\n  \"fields\": [\n    {\n      \"column\": \"Hours\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 1,\n        \"min\": 6,\n        \"max\": 10,\n        \"num_unique_values\": 5,\n        \"samples\": [\n          7,\n          10,\n          8\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    },\n    {\n      \"column\": \"Pass\",\n      \"properties\": {\n        \"dtype\": \"number\",\n        \"std\": 0,\n        \"min\": 0,\n        \"max\": 1,\n        \"num_unique_values\": 2,\n        \"samples\": [\n          1,\n          0\n        ],\n        \"semantic_type\": \"\",\n        \"description\": \"\"\n      }\n    }\n  ]\n}"
            }
          },
          "metadata": {},
          "execution_count": 314
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.isnull().sum()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 147
        },
        "id": "-XUk05h-FqEx",
        "outputId": "a2945bfd-45bd-4e08-9880-acf2cb68af51"
      },
      "execution_count": 315,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Hours    0\n",
              "Pass     0\n",
              "dtype: int64"
            ],
            "text/html": [
              "<div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>0</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>Hours</th>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>Pass</th>\n",
              "      <td>0</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div><br><label><b>dtype:</b> int64</label>"
            ]
          },
          "metadata": {},
          "execution_count": 315
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.duplicated()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 397
        },
        "id": "QZTEpZK2K2ix",
        "outputId": "87ddd8c7-272c-4e2a-f685-acd4381c2ee2"
      },
      "execution_count": 316,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "0    False\n",
              "1    False\n",
              "2    False\n",
              "3    False\n",
              "4    False\n",
              "5    False\n",
              "6    False\n",
              "7    False\n",
              "8    False\n",
              "9    False\n",
              "dtype: bool"
            ],
            "text/html": [
              "<div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>0</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>0</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>1</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>2</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>3</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>4</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>5</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>6</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>7</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>8</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>9</th>\n",
              "      <td>False</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div><br><label><b>dtype:</b> bool</label>"
            ]
          },
          "metadata": {},
          "execution_count": 316
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "x = df_cancer.drop('target', axis=1)\n",
        "y = df_cancer['target']\n",
        "x_train, x_test, y_train, y_test = train_test_split(x, y, test_size=0.2, random_state=42)"
      ],
      "metadata": {
        "id": "B0C9rPZ4JIvZ"
      },
      "execution_count": 317,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "c28bb437",
        "outputId": "fd42406e-7aef-4fe7-cb6c-70739dd31c81"
      },
      "source": [
        "prediction = cancer_model.predict(x_test)\n",
        "print(prediction)"
      ],
      "execution_count": 318,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[1 0 0 1 1 0 0 0 1 1 1 0 1 0 1 0 1 1 1 0 1 1 0 1 1 1 1 1 1 0 1 1 1 1 1 1 0\n",
            " 1 0 1 1 0 1 1 1 1 1 1 1 1 0 0 1 1 1 1 1 0 1 1 1 0 0 1 1 1 0 0 1 1 0 0 1 0\n",
            " 1 1 1 1 1 1 0 1 1 0 0 0 0 0 1 1 1 1 1 1 1 1 0 0 1 0 0 1 0 0 1 1 1 0 1 1 0\n",
            " 1 0 0]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#accuracy\n",
        "accuracy = accuracy_score(y_test, prediction)\n",
        "print(accuracy)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "scr6ni1lKvd8",
        "outputId": "0254f034-38d0-4bed-b1cb-d6031fb09419"
      },
      "execution_count": 319,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0.956140350877193\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#confusion matric\n",
        "cm=confusion_matrix(y_test,prediction)\n",
        "print(cm)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Gh1scVW3L6_1",
        "outputId": "c37e4a28-c887-498e-ad49-21b94ec9d747"
      },
      "execution_count": 320,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[39  4]\n",
            " [ 1 70]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#classification report\n",
        "cr=classification_report(y_test,prediction)\n",
        "print(cr)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0EIK2UaBOORV",
        "outputId": "f389472c-c85d-4e18-bd6c-9038a788f279"
      },
      "execution_count": 321,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "              precision    recall  f1-score   support\n",
            "\n",
            "           0       0.97      0.91      0.94        43\n",
            "           1       0.95      0.99      0.97        71\n",
            "\n",
            "    accuracy                           0.96       114\n",
            "   macro avg       0.96      0.95      0.95       114\n",
            "weighted avg       0.96      0.96      0.96       114\n",
            "\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#pictorial representation\n",
        "sns.heatmap(cm,annot=True,fmt='d')\n",
        "plt.show()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 435
        },
        "id": "tYqNU59LOR0F",
        "outputId": "b940be18-2dbe-401c-ce60-bc30e9426690"
      },
      "execution_count": 322,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 640x480 with 2 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Day 9 (DecisionTreeClassifier)"
      ],
      "metadata": {
        "id": "Jx4zSb4lT-th"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "import numpy as np\n",
        "import pandas as pd\n",
        "import matplotlib.pyplot as plt\n",
        "import seaborn as sns\n",
        "from sklearn.model_selection import train_test_split\n",
        "from sklearn.tree import DecisionTreeClassifier, plot_tree\n",
        "from sklearn.metrics import accuracy_score, classification_report, confusion_matrix"
      ],
      "metadata": {
        "id": "lg2Zd3ISUAHR"
      },
      "execution_count": 103,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "data ={\n",
        "    \"Age\":[25,30,35,40,45,50,55,60,65,70],\n",
        "    \"Income\":[50000,60000,70000,80000,90000,100000,110000,120000,130000,140000],\n",
        "    \"Student\":[1,0,1,0,1,0,1,0,1,0],\n",
        "    \"Purchase\":[1,1,0,0,0,0,1,1,0,0]\n",
        "}"
      ],
      "metadata": {
        "id": "BH1R_dfXY3m4"
      },
      "execution_count": 104,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "df=pd.DataFrame(data)\n",
        "print(df)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "G5M1jmDpY6ri",
        "outputId": "d37158c8-199f-412a-d679-83638f211d41"
      },
      "execution_count": 105,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "   Age  Income  Student  Purchase\n",
            "0   25   50000        1         1\n",
            "1   30   60000        0         1\n",
            "2   35   70000        1         0\n",
            "3   40   80000        0         0\n",
            "4   45   90000        1         0\n",
            "5   50  100000        0         0\n",
            "6   55  110000        1         1\n",
            "7   60  120000        0         1\n",
            "8   65  130000        1         0\n",
            "9   70  140000        0         0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "df.shape"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0mOtMTTcY8zl",
        "outputId": "cce65f74-1893-42d1-a1cf-3f454ba7cc11"
      },
      "execution_count": 106,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "(10, 4)"
            ]
          },
          "metadata": {},
          "execution_count": 106
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "X=df.drop(\"Purchase\",axis=1)\n",
        "y=df[\"Purchase\"]"
      ],
      "metadata": {
        "id": "6_WEPJs8ZDNj"
      },
      "execution_count": 107,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "X_train,X_test,y_train,y_test=train_test_split(X,y,test_size=0.2,random_state=42)"
      ],
      "metadata": {
        "id": "69G75RK0ZGvN"
      },
      "execution_count": 108,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "model = DecisionTreeClassifier(\n",
        "    criterion='gini',\n",
        "    max_depth=3,\n",
        "    random_state=42\n",
        ")\n",
        "\n",
        "model.fit(X_train,y_train)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 80
        },
        "id": "1PqWSPP7ZMEC",
        "outputId": "2d7338f8-54e6-4122-b4f5-19aef2b7df79"
      },
      "execution_count": 109,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "DecisionTreeClassifier(max_depth=3, random_state=42)"
            ],
            "text/html": [
              "<style>#sk-container-id-3 {\n",
              "  /* Definition of color scheme common for light and dark mode */\n",
              "  --sklearn-color-text: #000;\n",
              "  --sklearn-color-text-muted: #666;\n",
              "  --sklearn-color-line: gray;\n",
              "  /* Definition of color scheme for unfitted estimators */\n",
              "  --sklearn-color-unfitted-level-0: #fff5e6;\n",
              "  --sklearn-color-unfitted-level-1: #f6e4d2;\n",
              "  --sklearn-color-unfitted-level-2: #ffe0b3;\n",
              "  --sklearn-color-unfitted-level-3: chocolate;\n",
              "  /* Definition of color scheme for fitted estimators */\n",
              "  --sklearn-color-fitted-level-0: #f0f8ff;\n",
              "  --sklearn-color-fitted-level-1: #d4ebff;\n",
              "  --sklearn-color-fitted-level-2: #b3dbfd;\n",
              "  --sklearn-color-fitted-level-3: cornflowerblue;\n",
              "\n",
              "  /* Specific color for light theme */\n",
              "  --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));\n",
              "  --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, white)));\n",
              "  --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));\n",
              "  --sklearn-color-icon: #696969;\n",
              "\n",
              "  @media (prefers-color-scheme: dark) {\n",
              "    /* Redefinition of color scheme for dark theme */\n",
              "    --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));\n",
              "    --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, #111)));\n",
              "    --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));\n",
              "    --sklearn-color-icon: #878787;\n",
              "  }\n",
              "}\n",
              "\n",
              "#sk-container-id-3 {\n",
              "  color: var(--sklearn-color-text);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 pre {\n",
              "  padding: 0;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 input.sk-hidden--visually {\n",
              "  border: 0;\n",
              "  clip: rect(1px 1px 1px 1px);\n",
              "  clip: rect(1px, 1px, 1px, 1px);\n",
              "  height: 1px;\n",
              "  margin: -1px;\n",
              "  overflow: hidden;\n",
              "  padding: 0;\n",
              "  position: absolute;\n",
              "  width: 1px;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-dashed-wrapped {\n",
              "  border: 1px dashed var(--sklearn-color-line);\n",
              "  margin: 0 0.4em 0.5em 0.4em;\n",
              "  box-sizing: border-box;\n",
              "  padding-bottom: 0.4em;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-container {\n",
              "  /* jupyter's `normalize.less` sets `[hidden] { display: none; }`\n",
              "     but bootstrap.min.css set `[hidden] { display: none !important; }`\n",
              "     so we also need the `!important` here to be able to override the\n",
              "     default hidden behavior on the sphinx rendered scikit-learn.org.\n",
              "     See: https://github.com/scikit-learn/scikit-learn/issues/21755 */\n",
              "  display: inline-block !important;\n",
              "  position: relative;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-text-repr-fallback {\n",
              "  display: none;\n",
              "}\n",
              "\n",
              "div.sk-parallel-item,\n",
              "div.sk-serial,\n",
              "div.sk-item {\n",
              "  /* draw centered vertical line to link estimators */\n",
              "  background-image: linear-gradient(var(--sklearn-color-text-on-default-background), var(--sklearn-color-text-on-default-background));\n",
              "  background-size: 2px 100%;\n",
              "  background-repeat: no-repeat;\n",
              "  background-position: center center;\n",
              "}\n",
              "\n",
              "/* Parallel-specific style estimator block */\n",
              "\n",
              "#sk-container-id-3 div.sk-parallel-item::after {\n",
              "  content: \"\";\n",
              "  width: 100%;\n",
              "  border-bottom: 2px solid var(--sklearn-color-text-on-default-background);\n",
              "  flex-grow: 1;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-parallel {\n",
              "  display: flex;\n",
              "  align-items: stretch;\n",
              "  justify-content: center;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  position: relative;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-parallel-item {\n",
              "  display: flex;\n",
              "  flex-direction: column;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-parallel-item:first-child::after {\n",
              "  align-self: flex-end;\n",
              "  width: 50%;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-parallel-item:last-child::after {\n",
              "  align-self: flex-start;\n",
              "  width: 50%;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-parallel-item:only-child::after {\n",
              "  width: 0;\n",
              "}\n",
              "\n",
              "/* Serial-specific style estimator block */\n",
              "\n",
              "#sk-container-id-3 div.sk-serial {\n",
              "  display: flex;\n",
              "  flex-direction: column;\n",
              "  align-items: center;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  padding-right: 1em;\n",
              "  padding-left: 1em;\n",
              "}\n",
              "\n",
              "\n",
              "/* Toggleable style: style used for estimator/Pipeline/ColumnTransformer box that is\n",
              "clickable and can be expanded/collapsed.\n",
              "- Pipeline and ColumnTransformer use this feature and define the default style\n",
              "- Estimators will overwrite some part of the style using the `sk-estimator` class\n",
              "*/\n",
              "\n",
              "/* Pipeline and ColumnTransformer style (default) */\n",
              "\n",
              "#sk-container-id-3 div.sk-toggleable {\n",
              "  /* Default theme specific background. It is overwritten whether we have a\n",
              "  specific estimator or a Pipeline/ColumnTransformer */\n",
              "  background-color: var(--sklearn-color-background);\n",
              "}\n",
              "\n",
              "/* Toggleable label */\n",
              "#sk-container-id-3 label.sk-toggleable__label {\n",
              "  cursor: pointer;\n",
              "  display: flex;\n",
              "  width: 100%;\n",
              "  margin-bottom: 0;\n",
              "  padding: 0.5em;\n",
              "  box-sizing: border-box;\n",
              "  text-align: center;\n",
              "  align-items: start;\n",
              "  justify-content: space-between;\n",
              "  gap: 0.5em;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 label.sk-toggleable__label .caption {\n",
              "  font-size: 0.6rem;\n",
              "  font-weight: lighter;\n",
              "  color: var(--sklearn-color-text-muted);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 label.sk-toggleable__label-arrow:before {\n",
              "  /* Arrow on the left of the label */\n",
              "  content: \"▸\";\n",
              "  float: left;\n",
              "  margin-right: 0.25em;\n",
              "  color: var(--sklearn-color-icon);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 label.sk-toggleable__label-arrow:hover:before {\n",
              "  color: var(--sklearn-color-text);\n",
              "}\n",
              "\n",
              "/* Toggleable content - dropdown */\n",
              "\n",
              "#sk-container-id-3 div.sk-toggleable__content {\n",
              "  max-height: 0;\n",
              "  max-width: 0;\n",
              "  overflow: hidden;\n",
              "  text-align: left;\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-toggleable__content.fitted {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-toggleable__content pre {\n",
              "  margin: 0.2em;\n",
              "  border-radius: 0.25em;\n",
              "  color: var(--sklearn-color-text);\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-toggleable__content.fitted pre {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 input.sk-toggleable__control:checked~div.sk-toggleable__content {\n",
              "  /* Expand drop-down */\n",
              "  max-height: 200px;\n",
              "  max-width: 100%;\n",
              "  overflow: auto;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 input.sk-toggleable__control:checked~label.sk-toggleable__label-arrow:before {\n",
              "  content: \"▾\";\n",
              "}\n",
              "\n",
              "/* Pipeline/ColumnTransformer-specific style */\n",
              "\n",
              "#sk-container-id-3 div.sk-label input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-label.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Estimator-specific style */\n",
              "\n",
              "/* Colorize estimator box */\n",
              "#sk-container-id-3 div.sk-estimator input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-estimator.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-label label.sk-toggleable__label,\n",
              "#sk-container-id-3 div.sk-label label {\n",
              "  /* The background is the default theme color */\n",
              "  color: var(--sklearn-color-text-on-default-background);\n",
              "}\n",
              "\n",
              "/* On hover, darken the color of the background */\n",
              "#sk-container-id-3 div.sk-label:hover label.sk-toggleable__label {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "/* Label box, darken color on hover, fitted */\n",
              "#sk-container-id-3 div.sk-label.fitted:hover label.sk-toggleable__label.fitted {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Estimator label */\n",
              "\n",
              "#sk-container-id-3 div.sk-label label {\n",
              "  font-family: monospace;\n",
              "  font-weight: bold;\n",
              "  display: inline-block;\n",
              "  line-height: 1.2em;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-label-container {\n",
              "  text-align: center;\n",
              "}\n",
              "\n",
              "/* Estimator-specific */\n",
              "#sk-container-id-3 div.sk-estimator {\n",
              "  font-family: monospace;\n",
              "  border: 1px dotted var(--sklearn-color-border-box);\n",
              "  border-radius: 0.25em;\n",
              "  box-sizing: border-box;\n",
              "  margin-bottom: 0.5em;\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-estimator.fitted {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "/* on hover */\n",
              "#sk-container-id-3 div.sk-estimator:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-3 div.sk-estimator.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Specification for estimator info (e.g. \"i\" and \"?\") */\n",
              "\n",
              "/* Common style for \"i\" and \"?\" */\n",
              "\n",
              ".sk-estimator-doc-link,\n",
              "a:link.sk-estimator-doc-link,\n",
              "a:visited.sk-estimator-doc-link {\n",
              "  float: right;\n",
              "  font-size: smaller;\n",
              "  line-height: 1em;\n",
              "  font-family: monospace;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  border-radius: 1em;\n",
              "  height: 1em;\n",
              "  width: 1em;\n",
              "  text-decoration: none !important;\n",
              "  margin-left: 0.5em;\n",
              "  text-align: center;\n",
              "  /* unfitted */\n",
              "  border: var(--sklearn-color-unfitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-unfitted-level-1);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link.fitted,\n",
              "a:link.sk-estimator-doc-link.fitted,\n",
              "a:visited.sk-estimator-doc-link.fitted {\n",
              "  /* fitted */\n",
              "  border: var(--sklearn-color-fitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-fitted-level-1);\n",
              "}\n",
              "\n",
              "/* On hover */\n",
              "div.sk-estimator:hover .sk-estimator-doc-link:hover,\n",
              ".sk-estimator-doc-link:hover,\n",
              "div.sk-label-container:hover .sk-estimator-doc-link:hover,\n",
              ".sk-estimator-doc-link:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "div.sk-estimator.fitted:hover .sk-estimator-doc-link.fitted:hover,\n",
              ".sk-estimator-doc-link.fitted:hover,\n",
              "div.sk-label-container:hover .sk-estimator-doc-link.fitted:hover,\n",
              ".sk-estimator-doc-link.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "/* Span, style for the box shown on hovering the info icon */\n",
              ".sk-estimator-doc-link span {\n",
              "  display: none;\n",
              "  z-index: 9999;\n",
              "  position: relative;\n",
              "  font-weight: normal;\n",
              "  right: .2ex;\n",
              "  padding: .5ex;\n",
              "  margin: .5ex;\n",
              "  width: min-content;\n",
              "  min-width: 20ex;\n",
              "  max-width: 50ex;\n",
              "  color: var(--sklearn-color-text);\n",
              "  box-shadow: 2pt 2pt 4pt #999;\n",
              "  /* unfitted */\n",
              "  background: var(--sklearn-color-unfitted-level-0);\n",
              "  border: .5pt solid var(--sklearn-color-unfitted-level-3);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link.fitted span {\n",
              "  /* fitted */\n",
              "  background: var(--sklearn-color-fitted-level-0);\n",
              "  border: var(--sklearn-color-fitted-level-3);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link:hover span {\n",
              "  display: block;\n",
              "}\n",
              "\n",
              "/* \"?\"-specific style due to the `<a>` HTML tag */\n",
              "\n",
              "#sk-container-id-3 a.estimator_doc_link {\n",
              "  float: right;\n",
              "  font-size: 1rem;\n",
              "  line-height: 1em;\n",
              "  font-family: monospace;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  border-radius: 1rem;\n",
              "  height: 1rem;\n",
              "  width: 1rem;\n",
              "  text-decoration: none;\n",
              "  /* unfitted */\n",
              "  color: var(--sklearn-color-unfitted-level-1);\n",
              "  border: var(--sklearn-color-unfitted-level-1) 1pt solid;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 a.estimator_doc_link.fitted {\n",
              "  /* fitted */\n",
              "  border: var(--sklearn-color-fitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-fitted-level-1);\n",
              "}\n",
              "\n",
              "/* On hover */\n",
              "#sk-container-id-3 a.estimator_doc_link:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "#sk-container-id-3 a.estimator_doc_link.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-3);\n",
              "}\n",
              "</style><div id=\"sk-container-id-3\" class=\"sk-top-container\"><div class=\"sk-text-repr-fallback\"><pre>DecisionTreeClassifier(max_depth=3, random_state=42)</pre><b>In a Jupyter environment, please rerun this cell to show the HTML representation or trust the notebook. <br />On GitHub, the HTML representation is unable to render, please try loading this page with nbviewer.org.</b></div><div class=\"sk-container\" hidden><div class=\"sk-item\"><div class=\"sk-estimator fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-3\" type=\"checkbox\" checked><label for=\"sk-estimator-id-3\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>DecisionTreeClassifier</div></div><div><a class=\"sk-estimator-doc-link fitted\" rel=\"noreferrer\" target=\"_blank\" href=\"https://scikit-learn.org/1.6/modules/generated/sklearn.tree.DecisionTreeClassifier.html\">?<span>Documentation for DecisionTreeClassifier</span></a><span class=\"sk-estimator-doc-link fitted\">i<span>Fitted</span></span></div></label><div class=\"sk-toggleable__content fitted\"><pre>DecisionTreeClassifier(max_depth=3, random_state=42)</pre></div> </div></div></div></div>"
            ]
          },
          "metadata": {},
          "execution_count": 109
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "model = DecisionTreeClassifier(\n",
        "    criterion='entropy',\n",
        "    max_depth=3,\n",
        "    random_state=42\n",
        ")\n",
        "model.fit(X_train, y_train)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 80
        },
        "id": "IMgahgl3ZTVv",
        "outputId": "7d14b0e2-51c7-4caa-b09e-63c9f0d5eeeb"
      },
      "execution_count": 110,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "DecisionTreeClassifier(criterion='entropy', max_depth=3, random_state=42)"
            ],
            "text/html": [
              "<style>#sk-container-id-4 {\n",
              "  /* Definition of color scheme common for light and dark mode */\n",
              "  --sklearn-color-text: #000;\n",
              "  --sklearn-color-text-muted: #666;\n",
              "  --sklearn-color-line: gray;\n",
              "  /* Definition of color scheme for unfitted estimators */\n",
              "  --sklearn-color-unfitted-level-0: #fff5e6;\n",
              "  --sklearn-color-unfitted-level-1: #f6e4d2;\n",
              "  --sklearn-color-unfitted-level-2: #ffe0b3;\n",
              "  --sklearn-color-unfitted-level-3: chocolate;\n",
              "  /* Definition of color scheme for fitted estimators */\n",
              "  --sklearn-color-fitted-level-0: #f0f8ff;\n",
              "  --sklearn-color-fitted-level-1: #d4ebff;\n",
              "  --sklearn-color-fitted-level-2: #b3dbfd;\n",
              "  --sklearn-color-fitted-level-3: cornflowerblue;\n",
              "\n",
              "  /* Specific color for light theme */\n",
              "  --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));\n",
              "  --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, white)));\n",
              "  --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));\n",
              "  --sklearn-color-icon: #696969;\n",
              "\n",
              "  @media (prefers-color-scheme: dark) {\n",
              "    /* Redefinition of color scheme for dark theme */\n",
              "    --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));\n",
              "    --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, #111)));\n",
              "    --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));\n",
              "    --sklearn-color-icon: #878787;\n",
              "  }\n",
              "}\n",
              "\n",
              "#sk-container-id-4 {\n",
              "  color: var(--sklearn-color-text);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 pre {\n",
              "  padding: 0;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 input.sk-hidden--visually {\n",
              "  border: 0;\n",
              "  clip: rect(1px 1px 1px 1px);\n",
              "  clip: rect(1px, 1px, 1px, 1px);\n",
              "  height: 1px;\n",
              "  margin: -1px;\n",
              "  overflow: hidden;\n",
              "  padding: 0;\n",
              "  position: absolute;\n",
              "  width: 1px;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-dashed-wrapped {\n",
              "  border: 1px dashed var(--sklearn-color-line);\n",
              "  margin: 0 0.4em 0.5em 0.4em;\n",
              "  box-sizing: border-box;\n",
              "  padding-bottom: 0.4em;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-container {\n",
              "  /* jupyter's `normalize.less` sets `[hidden] { display: none; }`\n",
              "     but bootstrap.min.css set `[hidden] { display: none !important; }`\n",
              "     so we also need the `!important` here to be able to override the\n",
              "     default hidden behavior on the sphinx rendered scikit-learn.org.\n",
              "     See: https://github.com/scikit-learn/scikit-learn/issues/21755 */\n",
              "  display: inline-block !important;\n",
              "  position: relative;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-text-repr-fallback {\n",
              "  display: none;\n",
              "}\n",
              "\n",
              "div.sk-parallel-item,\n",
              "div.sk-serial,\n",
              "div.sk-item {\n",
              "  /* draw centered vertical line to link estimators */\n",
              "  background-image: linear-gradient(var(--sklearn-color-text-on-default-background), var(--sklearn-color-text-on-default-background));\n",
              "  background-size: 2px 100%;\n",
              "  background-repeat: no-repeat;\n",
              "  background-position: center center;\n",
              "}\n",
              "\n",
              "/* Parallel-specific style estimator block */\n",
              "\n",
              "#sk-container-id-4 div.sk-parallel-item::after {\n",
              "  content: \"\";\n",
              "  width: 100%;\n",
              "  border-bottom: 2px solid var(--sklearn-color-text-on-default-background);\n",
              "  flex-grow: 1;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-parallel {\n",
              "  display: flex;\n",
              "  align-items: stretch;\n",
              "  justify-content: center;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  position: relative;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-parallel-item {\n",
              "  display: flex;\n",
              "  flex-direction: column;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-parallel-item:first-child::after {\n",
              "  align-self: flex-end;\n",
              "  width: 50%;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-parallel-item:last-child::after {\n",
              "  align-self: flex-start;\n",
              "  width: 50%;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-parallel-item:only-child::after {\n",
              "  width: 0;\n",
              "}\n",
              "\n",
              "/* Serial-specific style estimator block */\n",
              "\n",
              "#sk-container-id-4 div.sk-serial {\n",
              "  display: flex;\n",
              "  flex-direction: column;\n",
              "  align-items: center;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  padding-right: 1em;\n",
              "  padding-left: 1em;\n",
              "}\n",
              "\n",
              "\n",
              "/* Toggleable style: style used for estimator/Pipeline/ColumnTransformer box that is\n",
              "clickable and can be expanded/collapsed.\n",
              "- Pipeline and ColumnTransformer use this feature and define the default style\n",
              "- Estimators will overwrite some part of the style using the `sk-estimator` class\n",
              "*/\n",
              "\n",
              "/* Pipeline and ColumnTransformer style (default) */\n",
              "\n",
              "#sk-container-id-4 div.sk-toggleable {\n",
              "  /* Default theme specific background. It is overwritten whether we have a\n",
              "  specific estimator or a Pipeline/ColumnTransformer */\n",
              "  background-color: var(--sklearn-color-background);\n",
              "}\n",
              "\n",
              "/* Toggleable label */\n",
              "#sk-container-id-4 label.sk-toggleable__label {\n",
              "  cursor: pointer;\n",
              "  display: flex;\n",
              "  width: 100%;\n",
              "  margin-bottom: 0;\n",
              "  padding: 0.5em;\n",
              "  box-sizing: border-box;\n",
              "  text-align: center;\n",
              "  align-items: start;\n",
              "  justify-content: space-between;\n",
              "  gap: 0.5em;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 label.sk-toggleable__label .caption {\n",
              "  font-size: 0.6rem;\n",
              "  font-weight: lighter;\n",
              "  color: var(--sklearn-color-text-muted);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 label.sk-toggleable__label-arrow:before {\n",
              "  /* Arrow on the left of the label */\n",
              "  content: \"▸\";\n",
              "  float: left;\n",
              "  margin-right: 0.25em;\n",
              "  color: var(--sklearn-color-icon);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 label.sk-toggleable__label-arrow:hover:before {\n",
              "  color: var(--sklearn-color-text);\n",
              "}\n",
              "\n",
              "/* Toggleable content - dropdown */\n",
              "\n",
              "#sk-container-id-4 div.sk-toggleable__content {\n",
              "  max-height: 0;\n",
              "  max-width: 0;\n",
              "  overflow: hidden;\n",
              "  text-align: left;\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-toggleable__content.fitted {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-toggleable__content pre {\n",
              "  margin: 0.2em;\n",
              "  border-radius: 0.25em;\n",
              "  color: var(--sklearn-color-text);\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-toggleable__content.fitted pre {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 input.sk-toggleable__control:checked~div.sk-toggleable__content {\n",
              "  /* Expand drop-down */\n",
              "  max-height: 200px;\n",
              "  max-width: 100%;\n",
              "  overflow: auto;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 input.sk-toggleable__control:checked~label.sk-toggleable__label-arrow:before {\n",
              "  content: \"▾\";\n",
              "}\n",
              "\n",
              "/* Pipeline/ColumnTransformer-specific style */\n",
              "\n",
              "#sk-container-id-4 div.sk-label input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-label.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Estimator-specific style */\n",
              "\n",
              "/* Colorize estimator box */\n",
              "#sk-container-id-4 div.sk-estimator input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-estimator.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-label label.sk-toggleable__label,\n",
              "#sk-container-id-4 div.sk-label label {\n",
              "  /* The background is the default theme color */\n",
              "  color: var(--sklearn-color-text-on-default-background);\n",
              "}\n",
              "\n",
              "/* On hover, darken the color of the background */\n",
              "#sk-container-id-4 div.sk-label:hover label.sk-toggleable__label {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "/* Label box, darken color on hover, fitted */\n",
              "#sk-container-id-4 div.sk-label.fitted:hover label.sk-toggleable__label.fitted {\n",
              "  color: var(--sklearn-color-text);\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Estimator label */\n",
              "\n",
              "#sk-container-id-4 div.sk-label label {\n",
              "  font-family: monospace;\n",
              "  font-weight: bold;\n",
              "  display: inline-block;\n",
              "  line-height: 1.2em;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-label-container {\n",
              "  text-align: center;\n",
              "}\n",
              "\n",
              "/* Estimator-specific */\n",
              "#sk-container-id-4 div.sk-estimator {\n",
              "  font-family: monospace;\n",
              "  border: 1px dotted var(--sklearn-color-border-box);\n",
              "  border-radius: 0.25em;\n",
              "  box-sizing: border-box;\n",
              "  margin-bottom: 0.5em;\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-0);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-estimator.fitted {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-0);\n",
              "}\n",
              "\n",
              "/* on hover */\n",
              "#sk-container-id-4 div.sk-estimator:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-2);\n",
              "}\n",
              "\n",
              "#sk-container-id-4 div.sk-estimator.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-2);\n",
              "}\n",
              "\n",
              "/* Specification for estimator info (e.g. \"i\" and \"?\") */\n",
              "\n",
              "/* Common style for \"i\" and \"?\" */\n",
              "\n",
              ".sk-estimator-doc-link,\n",
              "a:link.sk-estimator-doc-link,\n",
              "a:visited.sk-estimator-doc-link {\n",
              "  float: right;\n",
              "  font-size: smaller;\n",
              "  line-height: 1em;\n",
              "  font-family: monospace;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  border-radius: 1em;\n",
              "  height: 1em;\n",
              "  width: 1em;\n",
              "  text-decoration: none !important;\n",
              "  margin-left: 0.5em;\n",
              "  text-align: center;\n",
              "  /* unfitted */\n",
              "  border: var(--sklearn-color-unfitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-unfitted-level-1);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link.fitted,\n",
              "a:link.sk-estimator-doc-link.fitted,\n",
              "a:visited.sk-estimator-doc-link.fitted {\n",
              "  /* fitted */\n",
              "  border: var(--sklearn-color-fitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-fitted-level-1);\n",
              "}\n",
              "\n",
              "/* On hover */\n",
              "div.sk-estimator:hover .sk-estimator-doc-link:hover,\n",
              ".sk-estimator-doc-link:hover,\n",
              "div.sk-label-container:hover .sk-estimator-doc-link:hover,\n",
              ".sk-estimator-doc-link:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "div.sk-estimator.fitted:hover .sk-estimator-doc-link.fitted:hover,\n",
              ".sk-estimator-doc-link.fitted:hover,\n",
              "div.sk-label-container:hover .sk-estimator-doc-link.fitted:hover,\n",
              ".sk-estimator-doc-link.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "/* Span, style for the box shown on hovering the info icon */\n",
              ".sk-estimator-doc-link span {\n",
              "  display: none;\n",
              "  z-index: 9999;\n",
              "  position: relative;\n",
              "  font-weight: normal;\n",
              "  right: .2ex;\n",
              "  padding: .5ex;\n",
              "  margin: .5ex;\n",
              "  width: min-content;\n",
              "  min-width: 20ex;\n",
              "  max-width: 50ex;\n",
              "  color: var(--sklearn-color-text);\n",
              "  box-shadow: 2pt 2pt 4pt #999;\n",
              "  /* unfitted */\n",
              "  background: var(--sklearn-color-unfitted-level-0);\n",
              "  border: .5pt solid var(--sklearn-color-unfitted-level-3);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link.fitted span {\n",
              "  /* fitted */\n",
              "  background: var(--sklearn-color-fitted-level-0);\n",
              "  border: var(--sklearn-color-fitted-level-3);\n",
              "}\n",
              "\n",
              ".sk-estimator-doc-link:hover span {\n",
              "  display: block;\n",
              "}\n",
              "\n",
              "/* \"?\"-specific style due to the `<a>` HTML tag */\n",
              "\n",
              "#sk-container-id-4 a.estimator_doc_link {\n",
              "  float: right;\n",
              "  font-size: 1rem;\n",
              "  line-height: 1em;\n",
              "  font-family: monospace;\n",
              "  background-color: var(--sklearn-color-background);\n",
              "  border-radius: 1rem;\n",
              "  height: 1rem;\n",
              "  width: 1rem;\n",
              "  text-decoration: none;\n",
              "  /* unfitted */\n",
              "  color: var(--sklearn-color-unfitted-level-1);\n",
              "  border: var(--sklearn-color-unfitted-level-1) 1pt solid;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 a.estimator_doc_link.fitted {\n",
              "  /* fitted */\n",
              "  border: var(--sklearn-color-fitted-level-1) 1pt solid;\n",
              "  color: var(--sklearn-color-fitted-level-1);\n",
              "}\n",
              "\n",
              "/* On hover */\n",
              "#sk-container-id-4 a.estimator_doc_link:hover {\n",
              "  /* unfitted */\n",
              "  background-color: var(--sklearn-color-unfitted-level-3);\n",
              "  color: var(--sklearn-color-background);\n",
              "  text-decoration: none;\n",
              "}\n",
              "\n",
              "#sk-container-id-4 a.estimator_doc_link.fitted:hover {\n",
              "  /* fitted */\n",
              "  background-color: var(--sklearn-color-fitted-level-3);\n",
              "}\n",
              "</style><div id=\"sk-container-id-4\" class=\"sk-top-container\"><div class=\"sk-text-repr-fallback\"><pre>DecisionTreeClassifier(criterion=&#x27;entropy&#x27;, max_depth=3, random_state=42)</pre><b>In a Jupyter environment, please rerun this cell to show the HTML representation or trust the notebook. <br />On GitHub, the HTML representation is unable to render, please try loading this page with nbviewer.org.</b></div><div class=\"sk-container\" hidden><div class=\"sk-item\"><div class=\"sk-estimator fitted sk-toggleable\"><input class=\"sk-toggleable__control sk-hidden--visually\" id=\"sk-estimator-id-4\" type=\"checkbox\" checked><label for=\"sk-estimator-id-4\" class=\"sk-toggleable__label fitted sk-toggleable__label-arrow\"><div><div>DecisionTreeClassifier</div></div><div><a class=\"sk-estimator-doc-link fitted\" rel=\"noreferrer\" target=\"_blank\" href=\"https://scikit-learn.org/1.6/modules/generated/sklearn.tree.DecisionTreeClassifier.html\">?<span>Documentation for DecisionTreeClassifier</span></a><span class=\"sk-estimator-doc-link fitted\">i<span>Fitted</span></span></div></label><div class=\"sk-toggleable__content fitted\"><pre>DecisionTreeClassifier(criterion=&#x27;entropy&#x27;, max_depth=3, random_state=42)</pre></div> </div></div></div></div>"
            ]
          },
          "metadata": {},
          "execution_count": 110
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "y_pred=model.predict(X_test)"
      ],
      "metadata": {
        "id": "glMsPZ5RZX8O"
      },
      "execution_count": 111,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "print(y_pred)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "ITov76CcZajA",
        "outputId": "dccce14a-26ad-42dd-eee7-34075caf894c"
      },
      "execution_count": 112,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[1 1]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(y_test.values)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "lc6pCj5uZdHo",
        "outputId": "ffd0cfba-89eb-43a4-a304-ed6bea361a0b"
      },
      "execution_count": 113,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[0 1]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "accuracy_score=accuracy_score(y_test,y_pred)\n",
        "print(accuracy_score)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "jcK_W7PrZfy6",
        "outputId": "f46b276c-5029-4a9a-e7aa-1b090781e3ef"
      },
      "execution_count": 114,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0.5\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#classification\n",
        "cr=classification_report(y_test,y_pred)\n",
        "print(cr)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "oQGMuIweZhdP",
        "outputId": "1396fa29-4f90-444f-8091-e28d84700a16"
      },
      "execution_count": 115,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "              precision    recall  f1-score   support\n",
            "\n",
            "           0       0.00      0.00      0.00         1\n",
            "           1       0.50      1.00      0.67         1\n",
            "\n",
            "    accuracy                           0.50         2\n",
            "   macro avg       0.25      0.50      0.33         2\n",
            "weighted avg       0.25      0.50      0.33         2\n",
            "\n"
          ]
        },
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.\n",
            "  _warn_prf(average, modifier, f\"{metric.capitalize()} is\", len(result))\n",
            "/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.\n",
            "  _warn_prf(average, modifier, f\"{metric.capitalize()} is\", len(result))\n",
            "/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.\n",
            "  _warn_prf(average, modifier, f\"{metric.capitalize()} is\", len(result))\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [],
      "metadata": {
        "id": "vA4CNIk0bhAQ"
      },
      "execution_count": 115,
      "outputs": []
    }
  ]
}
