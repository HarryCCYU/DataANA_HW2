# DataANA_HW2
本次作業實做Decision tree，我使用的資料集來自公開的法律審判網站。
本次使用違反汽車運輸業管理規則遭吊扣牌照上訴撤銷的資料，其中以判決勝訴敗訴當作label，選取五個變數當作features。
五個變數分別為:累犯、自用車、生計、營利、舉證。
one hot encoding feature rule:
f1:犯第二次以上，是為1，否為0
f2:是否為自用車，是為1，否為0
f3:是否使用此吊扣牌照的車子賴以為生，例如:送貨的卡車、計程車，是為1，否為0
f4:是否有營利行為發生，是為1，否為0
f5:是否有民眾舉證辯護，是為1，否為0
