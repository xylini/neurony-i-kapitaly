# Instrukcja
### Przygotowanie środowiska
* utworzyć virtualne środowisko python3

    `python -m venv venv`
    
* na posiomie głównego folderu uzuskać dostęp do utworzonego środowiska

    `source venv/bin/activate`
    
* zainstalować w nim wymagane zależności

    `pip install -r requirements.txt`
    
* na poziomie katalogu głównego uruchomić `jupyter notebook` który będzie korzystać z virtualnego środowiska python3

### Uruchomienie projektu

* faza I - przygotowanie danych
    * Jeżeli uruchomienie projektu w celu ewaluacji wyników ten krok można pominąć ponieważ dane zostały uprzednio przeprocesowane i zapisane
    * W innym przypadku należy uruchomić kolejno wszystkie krotki w notebooku `phase_I_datapreparation.ipynb`
    
* faza II - sieć neuronowa
    * Szkolenie sieci neuronowej również można pominąć jeżeli projekt jest uruchamiany w celu sprawdzenia wyników i działania narzędzia ponieważ wytrenowany model został już zapisany do pliku `saved_model.h5`
    * W innym przypadku należy uruchomić kolejno wszystkie krotki w notebooku `phase_II.1_data_mapping.ipynb` a następnie w `phase_II.2_nerual_network.ipynb`
    
* faza III - algorytm ewolucyjny
    * Krok ten wystarcza w celu ewaluacji działania narzędzia
    * Należy uruchomić kolejno wszystkie komórki w jupyter notebooku
 