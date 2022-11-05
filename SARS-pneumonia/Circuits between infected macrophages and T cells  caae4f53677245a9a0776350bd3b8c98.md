# Circuits between infected macrophages and T cells in SARS-CoV-2 pneumonia

## Overview:

Pobrano próbki od 88 pacjentów z poważnym stanem SARS-CoV-2 oraz od 211 pacjentów z zapaleniem płuc spowodowanym innymi patogenami. Wysoki procent śmiertelności wśród pacjentów z ostrym zapaleniem płuc w połączeniu z ogólną reakcją zapalną, doprowadziła do wniosku że zapalenie płuc spowodowane przez SARS-CoV-2 różni się od tego wywołanego przez inne patogeny. Celem badania było zbadanie patobiologii wirusa SARS-CoV-2 oraz wyjaśnienie różnic w przebiegu ostrego zapalenia płuc spowodowanego przez SARS-CoV-2, w porównaniu z przebiegiem zapalenia płuc spowodowanego innymi patogenami. 

## Year: 2021

## Problems addressed:

Jak odpowiedź układu odpornościowego na skutek wirusa SARS-CoV-2 infekującego pęcherzyki płuc, różni się od innych typów zapalenia płuc?

## Methods:

Próbki z BAL zostały zbadane za pomocą:

- flow cytometry
- bulk transcriptomic profling

oraz na próbkach BAL zebranych mniej niż 48h po intubacji (próbki od 10 pacjentów): 

- single-cell RNA sequencing

Klasteryzacja genów:

- *q* < 0.05, likelihood-ratio test
- k-means clustering

Do wykrycia wirusów w makrofagach pęcherzyków płucnych zrobiono alignment odczytów RNA-seq do hybrydowego genomu człowieka/SARS-CoV-2/ influenzaA/California/07/2009

## Results:

Na podstawie wyników badań zaproponowano model dla patobiologii wirusa SARS.CoV-2. Model zaproponowany przez autorów mówi, że SARS-CoV-2 początkowo infekuje i replikuje się w nabłonku komórek nosogradzieli (*ang. nasopharynx*). Następnie wirus dostaje się do dalekich pęcherzyków płucnych. Tam infekuje komórki pęcherzyków płucnych oraz TRAMs (*ang. tissue-resident alveolar macrophages*). Na skutek tego rekrutowane są komórki pamięci T do TRAMs.

Pomimo że TRAMs są komórkami które słabo prezentują antygeny i nie aktywują natywnych komórek pamięci T, to niski poziom prezentacji przez makrofagi w pęcherzykach mógł być wystarczający do aktywowanie wcześniej istniejących komórek pamięci T, które reagują z  SARS-CoV-2. Istnienie takiej reakcji zostało potwierdzone dla  SARS-CoV i  SARS-CoV-2. Większą część takich obserwacji stanowią komórki zaobserwowane u ludzi starszych oraz u pacjentów z zaawansowanym stadium COVID-19. Ten mechanizm może tłumaczyć dlaczego SARS-CoV-2 dotyka dysproporcjonalnie wielu ludzi starszych.

 Komórki pamięci się aktywują, uwalniają IFNy, co powoduje dalszą produkcję chemokinin i cytokinin przez TRAM. Komórki pamięci T namnażają się i dalej produkują IFNy, co w końcu prowadzi do śmierci TRAM i rekrutacji MoAMs. Następnie zarażane są one przez SARS-CoV-2 co podtrzymuje pętle sygnalizacji stanu zapalnego. Zainfekowane makrofagi mogą pełnić rolę “konia trojańskiego”, transportując wirusa w inne rejony płuc. 

![Untitled](Circuits%20between%20infected%20macrophages%20and%20T%20cells%20%20caae4f53677245a9a0776350bd3b8c98/Untitled.png)

Obserwowaliśmy większe stężenie komórek limfocytów T CD4+ i CD8+ w pęcherzykach u pacjentów z SARS-CoV w stosunku do pacjentów z zapaleniem płuc innego pochodzenia. Dane z scRNA-seq potwierdziły że INFy jest produkowany zarówno przez komórki CD4+ i CD8+. 

Białka SARS-CoV-2 blokują odpowiedzi na interferon typu I i w danych pochodzących z sekwencjonowania nie zauważono ekspresji tego interferonu. Dane sugerują, że SARS-CoV-2 replikuje się w makrofagach pęcherzyków płuc, co jest zgodne z raportami o infekowaniu makrofagów przez SARS-CoV, MERS-CoV, i SARS-CoV-2 in vitro oraz z wykryciem SARS-CoV-2 w makrofagach pęcherzyków płuc podczas autopsji pacjentów chorych na zapalenie płuc spowodowane przez SARS-CoV-2. 

Infekcja makrofagów w pęcherzykach może być skutkiem fagocytozy zainfekowanej komórki nabłonka, a następnie wydostania się wirusa z lizosomu. Drugą hipotezą jest infekcja bezpośrednia makrofagów, co zostało potwierdzone dla SARS-CoV-2 i MERS-CoV. Ostatnia opcją jest antibody-dependent enhancement (ADE), które zostało zasugerowane na podstawie modeli SARS-CoV i MERS-CoV.

Zaproponowany model wyjaśnia niektóre unikalne cechy SARS-CoV-2 w tym niezwykle długi przebieg kliniczny w porównaniu do innych wirusów dróg oddechowych. 

## Questions

## Abstract:

Some patients infected with severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) develop severe pneumonia and acute respiratory distress syndrome[1](https://www.nature.com/articles/s41586-020-03148-w#ref-CR1)
 (ARDS). Distinct clinical features in these patients have led to speculation that the immune response to virus in the SARS-CoV-2-infected alveolus differs from that in other types of pneumonia[2](https://www.nature.com/articles/s41586-020-03148-w#ref-CR2)
. Here we investigate SARS-CoV-2 pathobiology by characterizing the immune response in the alveoli of patients infected with the virus. We collected bronchoalveolar lavage fluid samples from 88 patients with SARS-CoV-2-induced respiratory failure and 211 patients with known or suspected pneumonia from other pathogens, and analysed them using flow cytometry and bulk transcriptomic profiling. We performed single-cell RNA sequencing on 10 bronchoalveolar lavage fluid samples collected from patients with severe coronavirus disease 2019 (COVID-19) within 48 h of intubation. In the majority of patients with SARS-CoV-2 infection, the alveolar space was persistently enriched in T cells and monocytes. Bulk and single-cell transcriptomic profiling suggested that SARS-CoV-2 infects alveolar macrophages, which in turn respond by producing T cell chemoattractants. These T cells produce interferon-γ to induce inflammatory cytokine release from alveolar macrophages and further promote T cell activation. Collectively, our results suggest that SARS-CoV-2 causes a slowly unfolding, spatially limited alveolitis in which alveolar macrophages containing SARS-CoV-2 and T cells form a positive feedback loop that drives persistent alveolar inflammation.

## Glossary:

- ACE2- receptor dla SARS-CoV-2
- BAL - to procedura, którą wykonuje się w celu uzyskania próbek płynu z pęcherzyków płucnych
- IFNy - interferon gamma, interferon typu II  produkowany przez limfocyty
- MoAMs - *monocyte-derived alveolar macrophages*
- TRAM - *tissue-resident alveolar macrophages*
- SOFA - *sequential organ failure assessment score*
- APS - *acute physiology score*
- ADE - (*antibody-dependent enhancement*) occurs when the antibodies generated during an immune response recognize and bind to a pathogen, but they are unable to prevent infection. Instead, these antibodies act as a “Trojan horse,” allowing the pathogen to get into cells and exacerbate the immune response.