# 🛒 Sistema de Compras
> Aplicativo Android em **Java** para selecionar suas compras.

---

## 📱 Visão Geral

O **Sistema de Compras** é um aplicativo Android desenvolvido para facilitar as **Compras** do seu mercado.  
Com uma **interface moderna e intuitiva**, o app permite selecionar os produtos requeridos e clicando no botão ele exibe um card com total das compras.

---

## 🚀 Funcionalidades

✅ **Seleção** – Selecionar os produtos

✅ **Exibição Inteligente** – Exibição em card com preço total das compras

✅ **Interface Moderna** – Interface desenhada com altos detalhes de um mercado

✅ **Funcionalidade** – Funcionalidade simples, bastantado apenas selecionar e clicar no botão

---

## 🛠️ Tecnologias Utilizadas

- **Java** – Linguagem principal
- **Android SDK** – Framework de desenvolvimento
- **XML** – Criação de layouts e interfaces
- **Material Design** – Componentes de UI modernos
- **LinearLayout e RelativeLayout** – Layouts organizados
- **Gradle** – Gerenciamento de dependências

---

## ⚙️ Como Executar

**Pré-requisitos:**
- Android Studio (versão mais recente)
- Emulador Android ou dispositivo físico com API 21+

**Passos:**
```bash
# 1. Clone o repositório
git clone https://github.com/EleandersonRosadeMorais/Sistema-de-Compras

# 2. Acesse a pasta
cd Sistema-de-Compras

# 3. Abra no Android Studio
"C:\Program Files\Android\Android Studio\bin\studio64.exe" .

# 4. Execute o app
# (Shift + F10 ou Run 'app')
```

---

## 📂 Estrutura do Projeto

```bash
📦 app
├── 📂 manifests/
│   └── AndroidManifest.xml
├── 📂 java/
│   └── 📂br.com.ulbra/
│       └── MainActivity.java
└── 📂 res/
     ├── 📂 drawable/
     │   └── fundo.png
     ├── 📂 layout/
     │   └── activity_compras.xml
     ├── 📂 mipmap/
     ├── 📂 values/
     └── 📂 xml/
 📂 Gradle Scripts/
```

---

## 💻 Exemplo de Código

```java
            public void onClick(View arg0) {
                double total = 0;
                if (chkarroz.isChecked()) { total += 2.69; }
                if (chkleite.isChecked()) { total += 5.00; }
                if (chkcarne.isChecked()) { total += 9.7; }
                if (chkfeijao.isChecked()) { total += 2.30; }
                if (chkrefrigerante.isChecked()) { total += 2.00; }

                AlertDialog.Builder dialogo = new AlertDialog.Builder(MainActivity.this);
                dialogo.setTitle("Aviso");
                dialogo.setMessage("Valor total da compra: R$ "+ String.format("%.2f", total));
                dialogo.setNeutralButton("OK", null);
                dialogo.show();
            }
```

---

## 🎯 Objetivo do Projeto

Projeto desenvolvido com fins educacionais, com foco em:
- Práticas de programação **Java para Android**
- Uso de **Material Design** e boas práticas de UI/UX
- Estruturação e gerenciamento de dados no app
- Organização de código e arquitetura limpa
- Melhora continua da criatividade
- Desenvolvimento prático de **.xml** com **.java**

---

## 👤 Autor

**Eleanderson Rosa de Morais**  
📧 eleandersonmorais@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/eleanderson-rosa-de-morais-9aaab9324/)  
🔗 [GitHub](https://github.com/EleandersonRosadeMorais/)

---

## 💬 Contato

Dúvidas, sugestões ou colaborações?  
Entre em contato por email ou via redes sociais.  
Contribuições são bem-vindas! 🚀
