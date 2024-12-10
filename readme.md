# Eye Ball Move on Mousemove

Este projeto demonstra um efeito interativo onde "olhos" na tela seguem o movimento do cursor do mouse, criando uma experiência visual divertida e dinâmica.

## 📋 Funcionalidades

- **Olhos Dinâmicos:** Cada "olho" segue a posição do cursor do mouse em tempo real.
- **Movimento Suave:** O movimento é calculado com base no ângulo entre o centro do "olho" e a posição do mouse.


## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura do projeto.
- **CSS3:** Estilos
- **JavaScript:** Lógica de movimentação dos olhos.

## 🧩 Estrutura do Projeto

```
/
├── index.html    # Código principal HTML com o script embutido
├── style.css     # Arquivo de estilos

```


## 🚀 Como Executar

- Clonar ou Baixar o Repositório:

```bash
bash
Copiar código
git clone https://github.com/seu-usuario/eye-ball-move.git

```
- Abrir o Arquivo HTML: Abra o arquivo index.html diretamente no seu navegador para visualizar o efeito.



## 📖 Explicação do Código

- **JavaScript:**
  - A função eyeBall é chamada sempre que o mouse se move (mousemove).
  - Para cada "olho", é calculado o centro geométrico usando getBoundingClientRect.
  - A rotação é definida pela função Math.atan2 e aplicada via transform.

- **HTML:**
  - A estrutura HTML cria múltiplos "olhos" através de div com a classe .eye.


- **CSS:**
  - Os estilos definem a aparência dos olhos e garantem que o elemento central se comporte como uma pupila.


## 📌 Observações
- O número de "olhos" pode ser aumentado ou reduzido modificando as div dentro do contêiner .eyes.
- Certifique-se de que o arquivo style.css esteja corretamente vinculado para que o efeito visual seja exibido.

## 🖼️ Demonstração
Use o link a seguir para visualizar [Eye Follow](https://mardoniosc.github.io/EyesFollow/).

## 📄 Licença
Este projeto está licenciado sob a licença MIT. Sinta-se à vontade para usar, modificar e compartilhar!