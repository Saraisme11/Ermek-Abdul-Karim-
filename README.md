1. Қай жерде мұрагерлік қолданылды?

Мұрагерлік Account базалық класынан басқа кластарды жасау кезінде қолданылды:

SavingsAccount extends Account
CreditAccount extends Account

Яғни, барлық шоттар Account класынан мұра алады

2. Әдістер қалай қайта анықталды?

Полиморфизм method overriding арқылы жүзеге асады:

Мысалы:

deposit()
withdraw()

Әр класс бұл әдістерді өз ережесіне сай қайта жазады

Мысалы:

SavingsAccount → процент қосады
CreditAccount → қарыз лимитімен жұмыс істейді
3. Әр шоттың айырмашылығы неде?
SavingsAccount
Ақша сақтауға арналған
Процент (interest) қосылады
CreditAccount
Қарыз алуға болады
Лимит бар (overdraft)
