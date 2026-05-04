# SIS420-Laboratorio-07

Estudiante: Avendaño Retamozo Juan Antonio

Carrera: Ciencias de la Computación

Aprendizaje no supervisado, semi-supervisado y activo.

ChestMNIST es un dataset de imágenes médicas que forma parte de MedMNIST y está basado en radiografías de tórax del conjunto NIH ChestX-ray14. Consiste en imágenes en escala de grises redimensionadas a 28×28 píxeles, lo que lo hace ligero y útil para experimentación rápida en machine learning.

Es un problema de clasificación multi-label con 14 enfermedades, donde cada imagen se asocia a un vector binario que indica la presencia o ausencia de cada patología. Se utiliza principalmente con fines educativos y de benchmarking, ya que las etiquetas pueden contener ruido y la baja resolución limita su uso en aplicaciones clínicas reales.

El dataset ChestMNIST tiene 14 etiquetas (enfermedades), y cada una es binaria (presente = 1, ausente = 0). Son las siguientes:

1. Atelectasis
2. Cardiomegaly
3. Effusion
4. Infiltration
5. Mass
6. Nodule
7. Pneumonia
8. Pneumothorax
9. Consolidation
10. Edema
11. Emphysema
12. Fibrosis
13. Pleural Thickening
14. Hernia

[URL del dataset](https://zenodo.org/records/10519652)

[URL del cuadernillo](https://colab.research.google.com/drive/1aWQXX5ab14RPTAI9tC7KVS5HPUfHeZyy?usp=sharing)

El dataset original *chestMNIST_64* presentaba problemas de distribución desigual de etiquetas, por tanto se realizó un proceso de análisis y aumento de datos (data augmentation) para subsanar el desbalanceo. [URL del cuadernillo](https://colab.research.google.com/drive/1N0_oViQrA5fI9XghzevURvUkMnH3ZnFO?usp=sharing) / [URL del dataset procesado](https://drive.google.com/file/d/1XltQNArZSMvaDIfPgLF07D_TxWOGOSbY/view?usp=sharing)
