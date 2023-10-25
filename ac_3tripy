import openai

import senha

openai.api_key = senha.API_KEY

entrada = input('Digite sua pergunta: ')
saida = openai.ChatCompletion.create(model="gpt-3.5-turbo", messages=[{"role": "user", "content": entrada}])
print(saida.choices[0].message.content)
