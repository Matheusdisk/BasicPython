{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "fatecfatecfatecfatecfatec\n"
     ]
    }
   ],
   "source": [
    "print(5 * \"fatec\")"
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
      "Hello FATEC\n",
      "Bye\n"
     ]
    }
   ],
   "source": [
    "print(\"Hello FATEC\")\n",
    "print(\"Bye\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hello FATEC Bye\n"
     ]
    }
   ],
   "source": [
    "print(\"Hello FATEC\", end=\" \")\n",
    "print(\"Bye\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "4***5***6|||"
     ]
    }
   ],
   "source": [
    "print(4, 5, 6, sep=\"***\", end=\"|||\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Qual o valor do raio? 5\n",
      "Circunferência = 31.40\n"
     ]
    }
   ],
   "source": [
    "raio = float(input(\"Qual o valor do raio? \"))\n",
    "circunf = 2 * 3.14 * raio\n",
    "print(\"Circunferência = %.2f\" % circunf)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Digite um inteiro: 4\n",
      "O cubo é 64\n"
     ]
    }
   ],
   "source": [
    "numero = int(input(\"Digite um inteiro: \"))\n",
    "cubo = numero ** 3\n",
    "print(\"O cubo é \" + str(cubo))"
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
