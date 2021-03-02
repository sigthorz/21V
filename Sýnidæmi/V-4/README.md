# Sýnidæmi

Tabular Data <td> er eina tagið sem er hannað til að sækja gögn af miðlara í hvert sinn sem vefsíða er opnuð, jafnvel þegar flett er á milli síðna. Það er mjög gagnlegt þegar um er að ræða upplýsingar sem uppfærast daglega eða oftar.

Töflur henta ekki í útlithönnun ss til að birta texta og myndir sem breytast ekki. Vafrinn geymir slíkar upplýsingar í vinnsluminni sínu og birtir eftir þörfum. 

"Table" tagið er erfitt að eiga við þegar kemur að sveigjanleika vefsíðu og best að nota það ekki nema þegar um gagnvirkar færslur er að ræða.  


```
<table>
    <caption>Titill töflu</caption>
    <thead>
        <tr> 
            <th scope="col"> </th>
            <th scope="col">Forritun</th>
            <th scope="col">Vefþróun</th>
            <th scope="col">Gagnasöfn</th>
            <th scope="col">Tölvutækni</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td scope="row" data-label="Önn">1 önn</td>
            <td data-label="Forritun">FORR1FG05(AU)</td>
            <td data-label="Vefhönnun">VEFÞ1VG05(AU)</td>
            <td data-label="Gagnasöfn">GAGN1NG05(AU)</td>
            <td data-label="Tölvutækni">KEST1TR05(AU)</td>
        </tr>
        <tr>
            <td scope="row" data-label="Önn">2 önn</td>
            <td data-label="Forritun">FORR2FA05(BU)</td>
            <td data-label="Vefhönnun">VEFÞ2VH05(BU)</td>
            <td data-label="Gagnasöfn">GAGN2HS05(BU)</td>
            <td data-label="Tölvutækni">KEST2VJ05(BU)</td>
        </tr>
        <tr>
            <td scope="row" data-label="Önn">3 önn</td>
            <td data-label="Forritun">FORR2HF05(CU)</a></td>
            <td data-label="Vefhönnun">VEFÞ2VF05(CU)</a></td>
            <td data-label="Gagnasöfn">GAGN2VG05(CU)</a></td>
            <td data-label="Tölvutækni">KEST2UN05(CU)</a></td>
        </tr>
    </tbody>
</table>	
```

#### Markdown tafla

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

[Töflur í mardown rithætti](https://docs.github.com/en/github/writing-on-github/organizing-information-with-tables)
