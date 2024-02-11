# Unimore-CAD

    PRINCIPIO DI INDIPENDENZA
      la tolleranza dimensionale è indipendente dalla tolleranza geometrica

    TOLLERANZE GENERALI (ISO 2768 - mk) 
      Generali dimensionali  
        Fine - f  
        Media - m  
        Grossolana - c  
        Molto Grossolana - v  
    
      Geometriche genearli  
        fine - h  
        media - k  
        grossolana - l  
    

    TOLLERANZE GEOMETRICHE
      Deviazioni dalle dimensioni reali da quelle nominali che incidono su funzionalità o accoppiamenti. 
      A differenza delle tolleranze geometriche di Posizione, Oscillazione e Orientamento, 
        le tolleranze geometriche di Forma non sono associabili.
      Controllano lo scostamento di un elemento dalla sua forma, orientamento e posizione,
        considerate teoricamente esatte, senza considerare le dimensioni.
  

    TOLLERANZE DIMENSIONALI
      Errori macrogeometrici.
      Controllano le dimensioni locali reali di un elemento.
      Composto da Gradi ti tolleranza e scostamento fondamentale:
        Esistono 18 gradi di tolleranza normalizzata IT secondo lo standard ISO, da IT1 a IT18 con IT0 e IT01 utilizzati per casi speciali:
          IT7 alberi precisi-medi e fori precisi per alberi torniti e fori torniti o ottenuti tramite rettifica alesatura
          IT8 alberi e fori medi per alberi e fori ottenuti tra ite tornitura
  
          Lappatura: IT4
          Rettifica cilindrica: IT5, IT6, IT7
          Rettifica per piani: IT5, IT6, IT7, IT8
          Brocciatura: IT5, IT6, IT7
          Tornitura: IT6, IT7, IT8, IT9, IT10
          Alesatura: IT6, IT7, IT8, IT9
          Fresatura: IT7, IT8, IT9, IT10, IT11
          Trapanatura: IT10, IT11
          Tranciatura: IT10, IT11
          Formatura-stampaggio: IT11

        Lo scostamento fondamentale definisce la minima distanza (dimensione della posizione) dalla linea dello zero.
        Sono definiti 27 livelli, usando le lettere maiuscole per i fori e minuscole per gli alberi:
          da A(a) a H(h) sono scostamenti ineriori
          H(h) sono scostamenti nulli
          da K(k) a ZC(zc) sono scostamenti superiori
          J(j) e JS(js) sono scostamenti simmetrici rispetto alla linea dello 0
        Combiazioni FORO/albero comuni:
          con gioco
            H/f accoppiamenti rotanti, veloci e centraggio imperfetto
            H/g accoppiamenti rotanti, lenti e centraggio perfetto
            H/h scorrimeto, lento, precisissimo, lubrificante
          incerto
            H/j,k,m montaggio a mano, non può trasmettere sforzi
          iterferenza
            H/n,p montaggio forzato, può trasmettere sforzi

        Accoppiamenti raccomandati:
          con gioco
            H11/c11 o C11/h11  accoppiamento libero molto largo
            H9/d9 o D9/h9  accoppiamento libero largo
            H8/f7 o F8/h7  accoppiamento libero
            H7/g6 o G7/h6  accoppiamento libero stretto 
          incerto
            H7/h6 o H7/h6  per parti non detinate a muoversi
            H7/k6 o K7/h6  accurata centratura, una via di mezzo tra gioco e interferenza  
            H7/n6 o N7/H6  centratura molto accurata, è consentita una maggiore interferenza
          interferenza
            H7/p6 o P7/h6  accoppiamento con interferenza, ma senza particolari pressioni
            H7/s6 o S7/h6  accoppiamento con interferenze per parti in acciaio, o per parti a spessore sottile che devono essere forzate a caldo
            H7/u6 o U7/h6  accoppiamento con bloccaggio fortissimo per parti che non possono essere separate senza subire danni permanenti

    RUGOSITÀ DEL MATERIALE
      Errori microgeometrici.
      Simbolo chiuso per indicare una asportazione di truciolato
      Simbolo con un cerchio alla base per indicare nessuna lavorazione
      Valori tipici:
          Ra 6,3 per superficie di tenuta per flange con guarnizioni comuni
          Ra 3,2 per perni e cuscinetti per trasmissioni a mano, superfici di accoppiamento di parti smontabili (flange)
          Ra 1,6 per facce particolari di ingranaggi, alberi e fori ingranaggi, teste cillindro, scatole ingranaggi in ghisa, faccia pistone, superficie di tenuta flange con guarnizioni metalliche
          Ra 0,8 per freni, tamburi, fori brocciati, cuscinetti bronzo, PARTI DI PRECISIONE, denti ingranaggi, cuscinetti rettificati, superficie di tenuta di falange senza guarnizione, perni di alberi a gomito e portate di linee alberi, cuscinetti di metallo bianco, superficie di parti scorrevoli come pattini e relative guide, superficie di tenuta dei seggi valvole motore.
          
