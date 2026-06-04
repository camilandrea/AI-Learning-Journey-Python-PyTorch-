# AI Learning Journey: Python + PyTorch

Repositorio de práctica para aprender inteligencia artificial con Python y PyTorch, organizado por módulos temáticos.

## Estructura del proyecto

```
.
├── fundamentos/    # Python, NumPy, Pandas, visualización
├── ml_clasico/     # Scikit-learn, algoritmos clásicos de ML
├── cv/             # Visión por computadora con PyTorch
├── nlp/            # Procesamiento de lenguaje natural
├── rl/             # Aprendizaje por refuerzo
└── setup/          # Configuración del entorno y utilidades
```

## Cómo correr cada módulo

### Requisitos previos

```bash
pip install -r requirements.txt
```

### Fundamentos

```bash
cd fundamentos
jupyter notebook
```

### ML Clásico

```bash
cd ml_clasico
jupyter notebook
```

### Visión por Computadora (CV)

```bash
cd cv
jupyter notebook
```

### NLP

```bash
cd nlp
jupyter notebook
```

### Aprendizaje por Refuerzo (RL)

```bash
cd rl
jupyter notebook
```

## Entorno recomendado

- Python 3.10+
- Jupyter Notebook o JupyterLab
- GPU opcional (CUDA compatible para PyTorch)

## Entorno verificado

| Paquete | Versión |
|---|---|
| Python | 3.12.9 |
| PyTorch | 2.12.0 (CPU) |
| NumPy | 2.4.6 |
| Pandas | 3.0.3 |
| Scikit-learn | 1.9.0 |
| Matplotlib | 3.10.9 |
| Jupyter | 5.9.1 |

> **Nota:** PyTorch se instaló en modo CPU. Si en algún momento quieres usar GPU (NVIDIA), podemos instalarlo con soporte CUDA por separado.
