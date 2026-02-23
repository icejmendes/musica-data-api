# Music Data

A música é a digital da humanidade. Mais do que uma sucessão de notas, ela é uma ferramenta de identidade e um dos maiores atos de resistência cultural da nossa história. De ritmos marginalizados que se tornaram vozes de nações a álbuns que serviram como manifestos políticos, cada artista e cada melodia carregam o peso de uma herança que recusa o silêncio.

Ao longo deste projeto, construiremos uma API REST que manterá viva a memória musical, transformando artistas e álbuns em ecos acessíveis — prontos para atravessar o tempo e continuar contando suas histórias.

## Domínios
	- Artistas:
		- id
		- nome
		- em_atividade
		- periodo_atividade
		- tipo [grupo, pessoa]
		- genero_musical [rock, mpb, grunge, hip-hop, rap, forro, samba, etc]

	- Albuns:
		- id
		- nome
		- nome_artista
		- data_lancamento
		- genero_musical [rock, mpb, grunge, hip-hop, rap, forro, samba, etc]
		- gravadora

### Criterios de aceitacao
	- Artistas:
		- cadastrar novos artistas
		- consultar artistas pelo nome
		- listar artistas cadastrados
		- atualizar o cadastro de um artista 
		- apagar artista cadastrado		
	- Albuns:
		- cadastrar novo album;
		- consultar por nome do album;
		- consultar pelo nome do artista;
		- consultar pelo genero musical;
		- consultar albuns do mesmo artista;
		- atualizar ou corrigir album cadastrado
		- apagar album

	- disponibilizar coleção com os testes realizados no postman ou insomnia
	- testes manuais (via requisição postman/insomnia):
		- evidência dos testes realizados
	- testes unitarios
	- Implementacao com separacao de camadas (dominio, dao, servico, controle)
	- Git Flow
	- Submeter a PR para avaliação

  
