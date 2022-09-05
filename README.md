# Colab_Install_OpenVINO_2022

Intel OpenVINO 2022.1提供很多安裝方式，在Google Colab上僅適用APT和PyPI方式安裝。

範例Install_OpenVINO2022_on_Colab_Python_Virtual_Envirment.ipynb 主要介紹PyPI安裝方式及安裝問題解決方式。

註1：若沒有建立虛擬環境直接使用安裝 !pip installl openvino 會產生很多套件包衝突。  
註2：在虛擬環境執行任何指令都要加上 !source openvino_env/bin/activate; 若沒有加，則會跑回Google Colab原始環境。  
