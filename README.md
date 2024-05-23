# projeto_IDV_escolher_bons_investimentos
 Projeto para auxiliar na escolha de bons investimentos

## Implementação do projeto
1. Ações inicias

a. Atualize o pip para a versão mais nova
```
# pip upgrade
python.exe -m pip install --upgrade pip

# verifica a versão isntalada
pip --version
```
b. Caso não possua o venv instalado
```
pip install venv
```
   c. Crie o ambiente virtual
```
python -m venv <nome do ambiente>
```
   d. Ative o ambiente virtual
   * No Windows
```
.\<nome_da_venv>\Scripts\Activate.ps1
```
   * No Linux
```
source <nome_da_venv>/bin/activate
```
   e. Crie as dependências para o sistema
```
pip install -r requirements.txt
```
2. Ações complementares
   * Sempre que instalar um novo pacote
```
pip freeze > requirements.txt
```
