# ECO_uptodate
#Bibliotecas
import pyautogui
import time
import pyperclip
import pandas as pd
import numpy as pn
import PyPDF2 as pyf 
from pathlib import Path


nome_arquivo = "dare36.pdf"
arquivo = pyf.PdfReader(nome_arquivo)

num_paginas =  len(arquivo.pages)
print(num_paginas)

informacoes = arquivo.metadata
print(informacoes)
