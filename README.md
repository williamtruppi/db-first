db-first

DATABASE -- NEGOZIO DI VIDEOGIOCHI
TABELLA – VIDEOGIOCO

•	Id – PRIMARYKEY UNIQUE NOTNULL AUTO_INCREMENT
•	Codice_a_barre – BIGINT NOTNULL UNIQUE
•	Titolo – VARCHAR(40) NOTNULL
•	Titolo_originale – VARCHAR(40) NOTNULL
•	Sinossi – TEXT
•	Recensione - TEXT
•	Piattaforma_di_gioco – VARCHAR (10) NOTNULL
•	Distributore – VARCHAR(15) 
•	Sviluppatore – VARCHAR(15) NOTNULL
•	Regione (esempio PAL / NTSC) – VARCHAR (4) NOTNULL
•	Voto_critica – TINYINT
•	Prezzo – FLOAT (4,2) NOTNULL
•	Prezzo_scontato -- FLOAT (4,2) NOTNULL
•	Quantità – TINYINT NOTNULL
•	Disponibilità ( esempio. disponibilie / in riassortimento / non disponibile) – VARCHAR(20)
•	Vietato_minori VARCHAR(2) NOTNULL
