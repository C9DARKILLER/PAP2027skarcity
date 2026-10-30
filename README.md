

skarcity

PAP 2027 – TGPSI, Escola Secundária de Vergílio Ferreira
Aluno: Leónidas Roberto Correia Santos da Moeda · Turma 12.o 13.a · N.o 16
Professor orientador: Jorge Silva

Descrição

O skarcity é um videojogo de tiro tático competitivo (PvP) no formato 2v2, desenvolvido para jogadores que procuram uma experiência de combate tensa, estratégica e focada no trabalho em equipa. Inspirado na ambientação e nas mecânicas de sobrevivência de The Last of Us, o jogo coloca quatro jogadores divididos em duas equipas numa arena fechada e simétrica. A partida é resolvida puramente por eliminação direta, sem contagem de pontos, sagrando-se vencedora a última equipa a manter-se com vida. O projeto resolve a falta de jogos de tiro focados estritamente na sobrevivência tática em equipas reduzidas e em cenários equilibrados.

Objetivos

• Desenvolver um jogo de tiro 2v2 funcional no Unreal Engine com mecânicas de combate, cobertura e sobrevivência em tempo real.
• Criar um mapa de arena simétrico que garanta condições de jogo equilibradas (fair play) para ambas as equipas.
• Implementar um sistema de autenticação de utilizadores e registo de histórico de partidas através de uma base de dados relacional (SGBD).

Funcionalidades


Núcleo mínimo (obrigatório)

• Sistema de movimentação, mira, disparo e mecânica de cobertura para os jogadores.
• Lógica de partida 2v2 por rondas com condição de vitória por eliminação total da equipa adversária.
• Arena de jogo 3D com design simétrico.
• Sistema de autenticação (login/registo) integrado com a base de dados.

Extras (se houver tempo)

• Gestão e limitação de recursos (munição e itens de cura limitados espalhados pela arena).
• Interface de utilizador (UI) para menu principal, seleção de personagem e painel de estatísticas individuais (vitórias/derrotas).

Tecnologias


Camada	Tecnologia
Interface / Motor de Jogo	Unreal Engine
Servidor / Linguagens	C++ / Blueprints
Base de dados	MySQL / PostgreSQL / SQLite
Outras	GitHub / Git, Blender (modelação 3D)


Base de dados (tabelas previstas)

• utilizadores (id_utilizador, username, email, palavra_passe, data_registo)
• partidas (id_partida, data_hora, duracao_segundos, equipa_vencedora_id)
• estatisticas_jogador (id_estatistica, id_utilizador, partidas_jogadas, vitorias, derrotas, eliminacoes)

Planeamento


Fase	Período	Estado
Análise e modelação da base de dados
