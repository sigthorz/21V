# Töflur

Tabular Data <td> er eina tagið sem er hannað til að sækja gögn af miðlara í hvert sinn sem vefsíða er opnuð, jafnvel þegar flett er á milli síðna. Það er mjög gagnlegt þegar um er að ræða upplýsingar sem uppfærast daglega eða oftar.

Töflur henta ekki í skipulagshönnun vefsíðu. Önnur tög henta betur fyrir texta og myndir. 
"Table" tagið er erfitt að eiga við þegar kemur að sveigjanleika vefsíðu og best að nota það ekki nema þegar um gagnvirkar færslur er að ræða.  En ef um tiltötlulega fáa dálka er að ræða er hægt að nota aðferð sem er [útskrýrð nánar hér](https://allthingssmitty.com/2016/10/03/responsive-table-layout/)

Notaðu töfluna hér að neðan sem grunn að þínu verkefni. Settu eigin texta og gildi í töfluna. 

```
<table>
    <caption>Titill töflu</caption>
    <thead>
        <tr> 
            <th scope="col"> </th>
            <th scope="col">A</th>
            <th scope="col">B</th>
            <th scope="col">C</th>
            <th scope="col">D</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td scope="row" data-label="AÖ">E</td>
            <td data-label="A">Atli</td>
            <td data-label="B">Bára</td>
            <td data-label="C">Cesar</td>
            <td data-label="D">Dóra</td>
        </tr>
        <tr>
            <td scope="row" data-label="AÖ">F</td>
            <td data-label="A">Atli</td>
            <td data-label="B">Bára</td>
            <td data-label="C">Cesar</td>
            <td data-label="D">Dóra</td>
        </tr>
        <tr>
            <td data-label="A">Atli</td>
            <td data-label="B">Bára</td>
            <td data-label="C">Cesar</td>
            <td data-label="D">Dóra</td>
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
