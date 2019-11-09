{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "ESTRUTURAS DE REPETIÇÃO - WHILE"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "FATEC\n",
      "FATEC\n",
      "FATEC\n",
      "FATEC\n",
      "FATEC\n"
     ]
    }
   ],
   "source": [
    "i = 0\n",
    "while(i <= 4):\n",
    "    print(\"FATEC\")\n",
    "    i = i + 1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Digite um número inteiro: 1\n",
      "Digite um número inteiro: 2\n",
      "Digite um número inteiro: 3\n",
      "Digite um número inteiro: 41\n",
      "Digite um número inteiro: 6\n",
      "Saindo do loop...\n"
     ]
    }
   ],
   "source": [
    "i = 0\n",
    "while(i <= 4):\n",
    "    a = int(input(\"Digite um número inteiro: \"))\n",
    "    if(a == 5):\n",
    "        break\n",
    "    i = i + 1\n",
    "print(\"Saindo do loop...\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Digite um número inteiro: 1\n",
      "Digite um número inteiro: 2\n",
      "Digite um número inteiro: 3\n",
      "Digite um número inteiro: 4\n",
      "Digite um número inteiro: 5\n",
      "Digite um número inteiro: 6\n",
      "Saindo do loop...\n"
     ]
    }
   ],
   "source": [
    "i = 0\n",
    "while(i <= 4):\n",
    "    a = int(input(\"Digite um número inteiro: \"))\n",
    "    if(a == 5):\n",
    "        continue\n",
    "    i = i + 1\n",
    "print(\"Saindo do loop...\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
