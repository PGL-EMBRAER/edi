# 🚛 Plataforma de Controle de Coletas - GitHub Pages

Uma plataforma **100% online** para controle e monitoramento de coletas através do upload e processamento de arquivos EDI (.txt).

![Status](https://img.shields.io/badge/Status-Online-brightgreen)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Ativo-blue)
![Frontend](https://img.shields.io/badge/Frontend-HTML%2FJS-orange)
![Sem Backend](https://img.shields.io/badge/Backend-N%C3%A3o%20Necess%C3%A1rio-red)

## 🌟 **FUNCIONA 100% NO GITHUB PAGES!**

Esta versão foi especialmente criada para funcionar diretamente no GitHub Pages, sem precisar instalar Python ou rodar servidor local.

## 🎯 Funcionalidades

- ✅ **Upload de Arquivos EDI** - Processamento automático de arquivos .txt
- ✅ **Extração de Dados** - WR, Invoice (coluna 26), colunas 5-8, data de coleta
- ✅ **Histórico Completo** - Visualização organizada de todos os registros
- ✅ **Estatísticas por Mês** - Contadores automáticos de coletas
- ✅ **Filtros Avançados** - Por mês (YYYY-MM) e número WR
- ✅ **Interface Responsiva** - Funciona em desktop e mobile
- ✅ **Armazenamento Local** - Dados salvos no navegador (localStorage)
- ✅ **Sem Instalação** - Funciona direto no navegador

## 🚀 Como Usar

### Opção 1: GitHub Pages (Recomendado)

1. **Ative o GitHub Pages** no seu repositório:
   - Vá em Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)

2. **Acesse sua plataforma:**
   - URL: `https://seu-usuario.github.io/nome-do-repositorio`

### Opção 2: Download Direto

1. **Baixe o arquivo `index.html`**
2. **Abra no navegador** (clique duplo)
3. **Pronto para usar!**

## 📊 Como Funciona

### Processamento de Arquivos EDI

O sistema processa arquivos .txt com estrutura EDI e extrai:

| Campo | Posição | Exemplo | Descrição |
|-------|---------|---------|-----------|
| WR Number | Coluna 2 | WR1004112 | Número de identificação |
| Invoice | Coluna 26 | 0183001791 | Número da fatura |
| Coluna 5 | Coluna 5 | 20250611 | Dados específicos |
| Coluna 6 | Coluna 6 | 283.0000 | Valores numéricos |
| Coluna 7 | Coluna 7 | 974.2915 | Valores numéricos |
| Coluna 8 | Coluna 8 | 974.2915 | Valores numéricos |
| Data Coleta | Última coluna | 20250611 | Data no formato YYYYMMDD |

### Armazenamento

- **Dados salvos no navegador** usando localStorage
- **Não precisa de servidor** ou banco de dados
- **Dados persistem** entre sessões
- **Backup manual** através de export/import

## 🔧 Configuração do GitHub Pages

### 1. Estrutura de Arquivos

```
seu-repositorio/
└── index.html    # Arquivo principal da plataforma
```

### 2. Ativar GitHub Pages

1. Vá em **Settings** do repositório
2. Clique em **Pages** no menu lateral
3. Em **Source**, selecione **Deploy from a branch**
4. Em **Branch**, selecione **main**
5. Em **Folder**, selecione **/ (root)**
6. Clique em **Save**

### 3. Acessar a Plataforma

Após alguns minutos, sua plataforma estará disponível em:
```
https://seu-usuario.github.io/nome-do-repositorio
```

## 📱 Interface

A plataforma possui:

- **Header com gradiente azul/roxo** e badge "100% ONLINE"
- **Seção de Upload** para arquivos EDI
- **Filtros de Busca** por mês e número WR
- **Histórico Visual** com cards organizados
- **Estatísticas por Mês** em formato de cards
- **Alertas Visuais** para feedback do usuário

## 🔍 Funcionalidades Detalhadas

### Upload e Processamento

1. **Selecione arquivo .txt** com estrutura EDI
2. **Clique em "Processar Arquivo"**
3. **Sistema valida** formato e estrutura
4. **Extrai dados** das colunas corretas
5. **Salva no localStorage** do navegador
6. **Exibe resultados** automaticamente

### Filtros e Busca

- **Filtro por Mês:** Campo tipo "month" para seleção fácil
- **Filtro por WR:** Busca parcial ou completa
- **Aplicação Instantânea:** Resultados atualizados em tempo real

### Estatísticas

- **Contagem por Mês:** Quantas coletas por período
- **Visualização em Cards:** Interface limpa e organizada
- **Ordenação Cronológica:** Meses mais recentes primeiro

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilização e responsividade
- **JavaScript ES6+** - Lógica da aplicação
- **localStorage** - Armazenamento local
- **FileReader API** - Leitura de arquivos
- **GitHub Pages** - Hospedagem gratuita

## 🔒 Segurança e Privacidade

- **Dados Locais:** Tudo fica no seu navegador
- **Sem Servidor:** Não há transmissão de dados
- **Sem Cookies:** Usa apenas localStorage
- **Código Aberto:** Todo código visível e auditável

## 📋 Requisitos

- **Navegador Moderno:** Chrome, Firefox, Safari, Edge
- **JavaScript Habilitado:** Necessário para funcionamento
- **localStorage Disponível:** Para salvar dados

## 🆘 Solução de Problemas

### Arquivo não é processado

1. **Verifique o formato:** Deve ser .txt
2. **Verifique a estrutura:** Colunas separadas por TAB
3. **Verifique o conteúdo:** Mínimo 29 colunas por linha

### Dados não aparecem

1. **Verifique o console:** Pressione F12 e veja erros
2. **Limpe o cache:** Ctrl+F5 para recarregar
3. **Teste outro navegador:** Pode ser problema específico

### GitHub Pages não funciona

1. **Verifique as configurações:** Settings → Pages
2. **Aguarde alguns minutos:** Deploy pode demorar
3. **Verifique o nome do arquivo:** Deve ser `index.html`

## 🎉 Vantagens desta Versão

- ✅ **Sem Instalação** - Funciona direto no navegador
- ✅ **Sem Servidor** - Não precisa rodar Python
- ✅ **GitHub Pages** - Hospedagem gratuita
- ✅ **Acesso Global** - Qualquer lugar com internet
- ✅ **Sem Dependências** - Apenas um arquivo HTML
- ✅ **Rápido** - Carregamento instantâneo
- ✅ **Seguro** - Dados ficam no seu navegador

## 📞 Suporte

Para problemas ou dúvidas:

1. **Verifique a documentação** acima
2. **Teste em navegador diferente**
3. **Verifique o console** do navegador (F12)
4. **Abra uma issue** no GitHub

---

**⭐ Se este projeto foi útil, considere dar uma estrela!**

**🚀 Acesse agora:** [Sua Plataforma no GitHub Pages]

