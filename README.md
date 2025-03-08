# Template de Assistente de Desenvolvimento React Native com TypeScript para Claude

Este repositório contém um template de instruções para transformar o Claude em um assistente especializado em desenvolvimento mobile moderno com React Native, Expo SDK 52 e Gluestack UI, focando em TypeScript. Com esse template, o Claude se torna uma ferramenta poderosa para ajudar desenvolvedores a escrever código limpo, bem tipado e seguindo as melhores práticas para aplicações móveis.

## Sobre

Este template instrui o Claude a:

- Utilizar TypeScript como linguagem padrão para todos os exemplos
- Focar em React Native, Expo SDK 52, Gluestack UI e outras tecnologias mobile modernas
- Fornecer código bem escrito, com tipagem completa e seguindo boas práticas
- Explicar conceitos e decisões de design de forma clara
- Organizar respostas de maneira estruturada e educativa
- Priorizar a performance e experiência do usuário em dispositivos móveis

## Como Usar

1. **Copie o template**: Abra o arquivo `template.md` e copie todo o conteúdo
2. **Cole no início da sua conversa com Claude**: Comece uma nova conversa com o Claude e cole o template como primeira mensagem
3. **Envie o template**: Depois que o Claude receber e processar o template, você pode começar a fazer suas perguntas relacionadas a desenvolvimento mobile

### Dicas de Uso

- O template funciona melhor com o Claude 3 Opus ou Claude 3.5 Sonnet ou versões superiores
- O efeito do template persiste durante toda a conversa - você não precisa reenviá-lo para cada pergunta
- Para conversas longas, você pode ocasionalmente lembrar o Claude para "continuar seguindo o template de desenvolvimento React Native com TypeScript"
- Se quiser modificar algum aspecto específico da resposta do Claude, você pode fazer solicitações diretas como "responda com mais exemplos de código" ou "explique em mais detalhes"

## Exemplos de Uso

Aqui estão alguns exemplos de perguntas que você pode fazer ao Claude após aplicar o template:

### Exemplo 1: Solicitar um componente específico

```
Crie um componente de formulário de login em React Native com Gluestack UI, 
incluindo validação de email e senha. O formulário deve ter um design 
responsivo e mostrar mensagens de erro apropriadas.
```

### Exemplo 2: Resolver um problema específico

```
Estou tendo um problema com inferência de tipos no meu hook personalizado para 
React Native. Como posso fazer com que o tipo de retorno seja inferido corretamente 
a partir do parâmetro genérico? Aqui está meu código atual:

function useData<T>(initialData: T) {
  const [data, setData] = useState<T>(initialData);
  // resto do código
}
```

### Exemplo 3: Aprender sobre um conceito

```
Explique como implementar navegação com Expo Router e como ela se compara com 
React Navigation. Quais são as melhores práticas para organizar as rotas em um 
aplicativo React Native usando Expo?
```

### Exemplo 4: Solicitar refatoração

```
Refatore esse componente para usar TypeScript e Gluestack UI apropriadamente:

function ProductCard({product, onPress, loading, error}) {
  if (loading) return <View><Text>Loading...</Text></View>
  if (error) return <View><Text>Error: {error}</Text></View>
  return (
    <Pressable onPress={onPress}>
      <View style={{padding: 10, borderWidth: 1, borderColor: '#ccc'}}>
        <Text style={{fontSize: 18, fontWeight: 'bold'}}>{product.name}</Text>
        <Text>${product.price}</Text>
        {product.inStock && <Text>Em estoque</Text>}
      </View>
    </Pressable>
  )
}
```

## Personalização

Você pode personalizar o template para se adequar melhor às suas necessidades:

1. Abra o arquivo `template.md`
2. Modifique as seções relevantes para enfatizar tecnologias ou padrões específicos
3. Adicione exemplos personalizados ou remova partes que não são relevantes para seu caso de uso
4. Salve as alterações e use o template modificado nas suas conversas com Claude

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões para melhorar o template:

1. Abra uma issue descrevendo sua sugestão
2. Envie um pull request com suas alterações
3. Compartilhe exemplos de uso bem-sucedidos

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.
