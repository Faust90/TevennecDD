### Attacco		

---

L'*Attacco* (*ATK*) indica l'abilità della creatura nel colpire i suoi avversari. 

Per attaccare una creatura, il *Giocatore* dovrà cliccarci sopra. Il [*Personaggio*](..\personaggio.md) dunque sferrerà un *Colpo* se ha la suddetta creatura a portata. Se dovesse essere troppo lontano, si avvicinerà ad essa per il percorso più breve, per poi attaccarla alla fine del movimento. I [*Mostri*](..\mostri.md) cercano autonomamente di avvicinarsi al *Giocatore*, per poi colpirlo appena è a portata. Per ogni *Colpo* effettuato, viene tirato un d20, che è il *Tiro del Colpo* al quale viene aggiunto il bonus di *ATK*. Se il risultato del *Tiro per Colpire* è uguale o superiore alla *DEF* del bersaglio, il *Colpo* ha successo. *ATK* è calcolato con la seguente formula
	
**Addestramento + [_AGI_](..\personaggio\caratteristiche.md) / 2**

Dove *Addestramento* è pari a +3, ma viene aggiunto solo ai *Colpi* effettuati con le armi nelle quali si ha, per l’appunto, *Addestramento*. Usando alcune armi magiche o indossando alcuni anelli o amuleti si può ottenere un bonus magico all’ *ATK*. Il valore di *ATK* non può essere mai minore di +0 o maggiore di +10.

Se il *Colpo* ha avuto successo, vengono inflitti i *Danni*, che vengono calcolati con la seguente formula
	
**Risultato Dado Arma + [_ROB_](..\personaggio\caratteristiche.md) / 2**

I *Colpi* inflitti possono essere mirati a particolari punti deboli dei nemici: questi *Colpi* vengono definiti *Colpi critici*. Se il risultato del *Tiro per Colpire* del *Colpo* più il bonus di [*MEN*](..\personaggio\caratteristiche.md) è maggiore od uguale a 20, si utilizza il risultato migliore per il *Dado Arma*. Le *Armi* magiche aggiungono dei danni extra con alcuni potenziamenti. Il danno inflitto può essere di diversi tipi:

*	**_Fisici_**: inflitti dalle armi non magiche e dai [*Mostri*](..\mostri.md)
*	**_Sovrannaturali_**: inflitti dalle armi magiche e da alcuni [*Mostri*](..\mostri.md)
*	**_Luce_**: inflitti dagli incantesimi del [*Personaggio*](..\personaggio.md) 
*	**_Tenebra_**: inflitti dagli incantesimi dei [*Mostri*](..\mostri.md)

Se chi subisce il danno ha *Resistenza* a quel tipo di danno, ogni volta che subirà danni di quel tipo ne ridurrà la quantità di 3. Se invece chi subisce il danno ha *Immunità* a quel tipo di danno, il danno subito è sempre uguale a 0. Se chi subisce il danno ha *Vulnerabilità* a quel tipo di danno, ogni volta che subirà danni di quel tipo subirà 3 danni in più.

Il tempo di esecuzione di un Attacco è fisso, a seconda del numero di *Colpi*. Per un attacco a *Colpo* singolo il tempo sarà pari a 1 sec, altrimenti per un attacco con due *Colpi* sarà uguale a 1.5 sec (0.75 sec per *Colpo*).