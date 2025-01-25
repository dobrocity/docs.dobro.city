---
icon: network-wired
---

# Посевной раунд

Этот документ описывает порядок проведения посевного раунда финансирования общества GBA2MG73BVQCWFKFWYI4AV4AL3JR3OXCRWELVID7ZEAMCA4CJUY7TEAM (далее - TEAM). 

В целях учета посевных инвестиций открыт аккаунт GAYUY3PO4RVXEHHOHPNYAIDVLHHLOZU6MULI37PZUDA7HSJLNOADSEED (далее - SEED). 

В мультиподпись SEED входят: 

- GDQGKR65EZWKPVO5UWLGEM3KLMW5UINXKNWGK6OKAY7PRVRBK5GVQR6N, вес 1
- GCPJUXPETZEIJNEAAEO2LGZIA6IQNNWGOHPNP4ZQECDS6IKKIGJO5LFV, вес 1
- GAQPZKOYGJDEWLYO6PBOJ4NG6HNBBNNZSOJNKUUCVJGLBQIQSO5AC26F, вес 1
- GBYH3M3REQM3WQOJY26FYORN23EXY22FWBHVZ74TT5GYOF22IIA7YSOX, вес 1
- GDUMK6YJZ6ZC72CAMVHLUHLIFTNSLD7WFWO75Q3T2EOEW75XWH4PNSOZ, вес 2
- GD6TPYDUKQU6TACMEQLEWSGGL2HWZRJ6LVVLRQYWJTGJS4RI5BD6NMIA, вес 1
- GCKWH4EEYSLJMGA5DOJYQFOBUV57PLJYXBA7I42ZERZEMRSVDT6WLEDS, вес 1

Акаунд SEED эмитрирует токен `INVEST` и выставляет ордер на обмен 11000 `INVEST` на 10000 `EURMTL`. 

Токены `INVEST` не являются голосующими или дивидендными. 

Публикуется объявление о проведении посевного раунда с согласованными сроками. 

По истечению срока посевного раунда аккаунт SEED 
- открывает линию доверия к токену `LOAN` аккаунта TEAM. 
- выставляет ордер на обмен набранного количества `EURMTL` на `LOAN` с интересом 10% (1 к 1.1).
- выставляет ордер на обмен набранного количества `LOAN` на `EURMTL` без интереса (1 к 1).

Подписанты SEED подписывают транзакцию со следующими операциями: 

- pre-authorized на выставление ордера на обмен `INVEST` на `EURMTL` по цене 1 к 1 с датой не ранее 00:00 UTC 1 января 2026 года в объеме привлеченных инвестиций. 
- выставление порогов в 9 (больше чем сумма весов подписантов)

Таким образом фиксируются долговые обязательства TEAM перед инвесторами SEED и фиксируется предварительно авторизованная транзакция на возврат инвестиций с интересом. 

TEAM обязуется выставить ордер на обмен `EURMTL` на `LOAN` без интереса (1 к 1) не позднее 1 января 2026 года 00:00 UTC с записью обязательства в блокчейн.

В случае недостаточности средств на аккаунте TEAM для выставления ордера на обмен `EURMTL` на `LOAN` (1 к 1) в объеме эмитированного `LOAN` к 1 января 2026 года 00:00 UTC, TEAM обязуется выставить ордер на продажу всех `EURMTL` на счетах GCDOXSSA6RKZHZGI5KI2RB24UWKFTKZ2CTKXG5WBAURDDYR3CER7DOBR и GDJSY7FCYCIPF5VRFV3H7QLLWH4F2MFQXSXNZQKH35J57AFKI4276QDF за токены `INVEST` по цене c интересом 10% (1.1 к 1) `EURMTL` за `INVEST` (обратный выкуп).    

Аккаунт TEAM выставляет ордер на обмен `LOAN` на `EURMTL` с интересом 10% (1.1 к 1) в объеме набранных SEED средств и принимает раунд инвестиций. 
