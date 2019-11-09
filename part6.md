{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "ESTRUTURAS DE REPETIÇÃO - FOR"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [],
   "source": [
    "#\"iterables\" em Python (strings, listas, tuplas, dicionários, conjuntos)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "F\n",
      "A\n",
      "T\n",
      "E\n",
      "C\n"
     ]
    }
   ],
   "source": [
    "for letra in \"FATEC\":\n",
    "    print(letra)"
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
      "2\n",
      "3\n",
      "4\n",
      "5\n",
      "6\n",
      "7\n"
     ]
    }
   ],
   "source": [
    "for x in [2, 3, 4, 5, 6, 7]:\n",
    "    print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "2\n",
      "4\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "lista = [2, 4, 5]\n",
    "for x in lista:\n",
    "    print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0\n",
      "1\n",
      "2\n",
      "3\n",
      "4\n",
      "5\n",
      "6\n",
      "7\n",
      "8\n",
      "9\n"
     ]
    }
   ],
   "source": [
    "for i in range(0, 10):\n",
    "    print(i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0\n",
      "2\n",
      "4\n",
      "6\n",
      "8\n"
     ]
    }
   ],
   "source": [
    "for i in range(0, 10, 2):\n",
    "    print(i)"
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
      "10\n",
      "9\n",
      "8\n",
      "7\n",
      "6\n",
      "5\n",
      "4\n",
      "3\n",
      "2\n",
      "1\n"
     ]
    }
   ],
   "source": [
    "for i in range(10, 0, -1):\n",
    "    print(i)"
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
