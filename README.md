# opgave-BEM
03:50
spaghetti kode er dårligt. Spaghetti kode er når man har kode som hænger sammen på mange måder og gør det uoverskueligt at holde styr på hvad der hører til hvad eller hvad der gør hvad. Single responsibility principle er når det har et specifikt og et formål. Man skal kunne forklare det kort hvad den gør uden at skulle sige "og" "eller" hvilket komplicerer koden.

05:20
Koden skal lave så det kan genbruges flere forskellige stedet. Man burde kunne tage stykker af koden ud og bruge den igen. Man vil helst have et objekt som ikke er connected til alt muligt andet.

06:30
Der bliver snakket om at man altid kan finde et mønster på hvordan tingene er sat op med css. Det Nicole fandt frem til at var men lige så godt kunne lave et "module" hvor at man havde en over class ".media" som har 2 children ".bd" og ".img". Det gør det nemme at sætte en side hvor at ting skal gentages op da du bare kan sætte denne kode ind hvor det skal stå. 

08:57
Introduction til BEM. BEM er en måde at navngive dine css classes. BEM står for "block-element-modifier" hvilke hentyder til koden. Det er en smart måde at navngive dine classes på da det er nemt at holde styr på fordi man kan opdele koden i forskellige sektioner. 

19:05
Jo mere specifik du er omkring hvordan du rammer din objekts jo bedre. Specificity spiller en stor rolle og man skal passe på med hvordan man bruger det da det kan skabe problemer meget nemt. Hvis du f.eks. siger a skal være color blue men efter siger a .awesome skal være color green så overrider a .awesome din originale a fordi det har flere specifikations.

20:05
Snakker videre om specificity, jo flere selectors du putter i classes jo større chance er der for at de overrider det andet. Derfor skal man passe på med at lave for mange kombi selectorer.

22:06
Undgå at bruge id for det kan du ikke override medmindre du har over 600 classes i en gammel version af explorer. Aldrig brug id til at style på ting med. Længere class navne men single selectors er nemmere og bedre at bruge end hvis du sætter 3 selectors sammen for at style. F.eks. ".body ul li" er værre end ".unordered-list-in-the-body" fordi det er nemmere at styrer .unordered-list-in-the-body da du ikke skal bruge meget for at kunne overgå den.

24:20
Selv hvis navnet er langt og uoverskueligt er det bedre at bruge da alle dem du laver har samme styrke niveau og derfor kan bliver kørt over nemmere og laves om på nemmere. Med den måde har du altid kontrol over hvad de gør og hvordan de reagere med hinanden. Husk at gøre ting nemmere for dig selv.

I videoen hører vi om hvordan BEM fungere og hvad det er. De kommer ind på hvorfor at kombi selectors er værre en enkelte selectors pga specificity. Der bliver også snakket om hvorfor id's ikke er gode at bruge til styling og derfor burde undgås. 
