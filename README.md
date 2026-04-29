## 🧹 Data Cleaning

- Am utilizat funcția de filtrare din Excel pentru a identifica valorile lipsă (blank) din setul de date. Această etapă a ajutat la înțelegerea distribuției datelor lipsă și la evaluarea impactului asupra calității datasetului.  

- Am utilizat funcția Find & Replace pentru a standardiza valorile lipsă reprezentate inconsistent (ex: „NA”), acestea fiind înlocuite cu celule goale pentru a asigura consistența datelor.  
![Image Alt](https://github.com/rzvrazor/excel-superstore-analysis/blob/2aa4d47f988af89f87d483c0b885c5a569798e2d/screenshots/2%20-%20Find%20Replace.png)

- Am verificat existența valorilor duplicate folosind funcția de identificare a duplicatelor din Excel. Acestea au fost evidențiate pentru evaluare, fără a fi eliminate în această etapă.  

- Coloana „Order Date” a fost convertită și standardizată în format de tip dată (Date), pentru a permite analiza corectă a datelor în funcție de timp.  

- Coloana „Sales” a fost verificată și convertită în format numeric, pentru a asigura corectitudinea calculelor și agregărilor.  


## 📊 Data Analysis

- A fost creat un tabel pivot pentru analiza vânzărilor în funcție de regiune și categorie de produse, folosind suma vânzărilor. Valorile au fost sortate descrescător pentru a evidenția cele mai performante combinații.  

- Pe baza acestuia, a fost realizat un grafic de tip column chart pentru vizualizarea distribuției vânzărilor, evidențiind categoriile cu cea mai mare contribuție la venituri.  

- Pentru o perspectivă completă, a fost creat un tabel pivot suplimentar bazat pe Profit, care permite identificarea regiunilor cu performanță financiară negativă.  


## 💡 Key Insights

- Categoria „Technology” generează cele mai mari vânzări în majoritatea regiunilor, fiind principalul motor de venit al companiei.  

- Regiunea „West” înregistrează cele mai ridicate valori ale vânzărilor, având o performanță constant superioară.  

- Analiza profitului arată că, deși există vânzări în toate regiunile, nivelul profitului este relativ scăzut. În regiunea „Central”, categoria „Furniture” înregistrează pierderi (profit negativ), indicând o posibilă problemă de rentabilitate.  
