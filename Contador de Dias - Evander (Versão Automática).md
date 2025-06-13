# Contador de Dias - Evander (Versão Automática)

## Descrição
Este é um contador de dias automático que calcula e exibe quantos dias se passaram desde uma data específica definida no código. O resultado é exibido automaticamente no formato: "Evander está há XX dias Sem arregar".

## Como Usar

1. **Abrir o Contador**: Abra o arquivo `contador-dias.html` em qualquer navegador web moderno.

2. **Visualizar o Resultado**: 
   - O contador é exibido automaticamente ao carregar a página
   - Não há necessidade de interação do usuário
   - O resultado é atualizado automaticamente a cada minuto

## Como Configurar a Data Inicial

Para alterar a data inicial, edite o arquivo `contador-dias.html`:

1. Abra o arquivo em um editor de texto
2. Localize a linha no JavaScript:
```javascript
const DATA_INICIAL = '2025-06-01'; // Altere esta data conforme necessário
```
3. Substitua `'2025-06-01'` pela data desejada no formato `AAAA-MM-DD`
4. Salve o arquivo
5. Recarregue a página no navegador

### Exemplos de Datas:
- `'2025-01-01'` para 1º de janeiro de 2025
- `'2024-12-25'` para 25 de dezembro de 2024
- `'2025-06-15'` para 15 de junho de 2025

## Características

### Funcionalidades
- ✅ Cálculo automático ao carregar a página
- ✅ Atualização automática a cada minuto
- ✅ Data inicial configurável no código
- ✅ Interface limpa sem campos de entrada
- ✅ Validação automática de datas
- ✅ Responsivo para dispositivos móveis

### Design
- 🎨 Gradiente de fundo moderno
- 📱 Design responsivo para mobile e desktop
- ✨ Animações CSS com efeito pulse no número
- 🎯 Interface minimalista e focada
- 🔄 Resultado sempre visível

### Comportamento
- 📅 Calcula automaticamente a diferença de dias
- 🔄 Atualiza o contador a cada minuto
- ⚠️ Mostra "0" se a data inicial for no futuro
- 🛡️ Tratamento de erros para datas inválidas

## Personalização

### Alterar Nome e Frase
Para personalizar o contador para outro nome ou frase:

1. Abra o arquivo `contador-dias.html`
2. Localize a seção do resultado:
```html
<div id="result" class="result">
    <div>Evander está há</div>
    <div id="daysCount" class="days-number">0</div>
    <div>dias</div>
    <div>Sem arregar</div>
</div>
```
3. Substitua "Evander" pelo nome desejado
4. Substitua "Sem arregar" pela frase desejada

### Alterar Cores
Para mudar as cores do contador, edite os estilos CSS:
- Fundo: Modifique o `background` em `.result`
- Gradiente da página: Altere o `background` em `body`

## Tecnologias Utilizadas
- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com gradientes e animações
- **JavaScript**: Lógica de cálculo automático e atualização

## Compatibilidade
- ✅ Chrome (versão 60+)
- ✅ Firefox (versão 55+)
- ✅ Safari (versão 12+)
- ✅ Edge (versão 79+)

## Exemplo de Uso
Com a data inicial configurada como `'2025-06-01'` e hoje sendo `13/06/2025`, o resultado será:
**"Evander está há 12 dias Sem arregar"**

## Vantagens da Versão Automática
- 🚀 **Simplicidade**: Sem necessidade de interação do usuário
- 🔒 **Configuração fixa**: Data inicial protegida no código
- ⚡ **Performance**: Carregamento instantâneo do resultado
- 🎯 **Foco**: Interface dedicada apenas ao resultado
- 🔄 **Atualização automática**: Sempre mostra o valor atual

---

*Versão automática criada para máxima simplicidade e eficiência!*

