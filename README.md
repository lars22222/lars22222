- 👋 Hi, I’m @lars22222
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
lars22222/lars22222 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
ggplot(data = projekt_aktuell,aes(x=Geschlecht,fill=`Oeffentlicher Dienst aktuell`))+
  geom_bar(position="dodge")+
  labs(x="Geschlecht",y="Anzahl")+
  scale_fill_discrete(name="Oeffentlicher Dienst")+
  theme_minimal()
  
