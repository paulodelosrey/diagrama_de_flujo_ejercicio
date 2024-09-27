graph TD
    A[Inicio] --> B[Solicitar presión en libras]
    B --> C[Solicitar temperatura en °C]
    C --> D{Presión >= 35 O \n35 < Temperatura < 95?}
    D -->|Sí| E[Alarma encendida]
    D -->|No| F[Alarma apagada]
    E --> G[Mostrar estado de la alarma]
    F --> G
    G --> H[Fin]
