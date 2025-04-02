# hellokitty
const facts = [
    "Mačke mogu skakati do šest puta više od svoje dužine.",
    "Mačke provode oko 70% svog života spavajući.",
    "Mačke mogu proizvesti više od 100 različitih zvukova.",
    "Najstarija zabeležena mačka živela je 38 godina.",
];

function showFact() {
    const fact = facts[Math.floor(Math.random() * facts.length)];
    document.getElementById("cat-fact").innerText = fact;
}


