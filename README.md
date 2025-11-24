
# README — Filosofía y Poder

Descripción  
Este repositorio contiene un mapa conceptual sobre la relación entre filosofía y poder, que recorre desde el Renacimiento hasta la filosofía postmoderna. El objetivo es ofrecer un resumen visual y explicativo de los principales autores, conceptos y preguntas éticas relacionadas con el ejercicio del poder.

Diagrama (Mermaid)  
Copia este bloque en un archivo README.md o en un visor que soporte Mermaid (GitHub soporta bloques ```mermaid```):

```mermaid
graph TD
    A[Filosofía y Poder] --> B[El Renacimiento y el Pensamiento Político Moderno]
    A --> C[Ilustración y Democracia]
    A --> D[Ética y Poder]
    A --> E[Filosofía Postmoderna y Desafíos al Poder]

    subgraph Renacimiento
        B --> B1["Maquiavelo\nSeparación moral y política\nRazón de Estado"]
        B --> B2["Hobbes\nContrato social\nLeviatán: poder absoluto para garantizar orden"]
        B --> B3["Transición\nde la teocracia\na la razón de Estado secular"]
    end

    subgraph Ilustración
        C --> C1["Rousseau\nVoluntad general\nSoberanía popular"]
        C --> C2["Montesquieu\nSeparación de poderes\nFrenos y contrapesos"]
        C --> C3["Kant\nIdea republicana\nLa paz perpetua"]
        C --> C4["Legado\nBases de los Derechos Humanos\ny la Democracia liberal"]
    end

    subgraph Ética
        D --> D1["Concepto central\nLímites morales del ejercicio del poder"]
        D --> D2["Preguntas clave\n¿Es legítimo el poder?\n¿Cómo se debe usar el poder?"]
        D --> D3["Enfoques\nUtilitarismo, Deontología,\nÉtica de la virtud"]
    end

    subgraph Postmodernidad
        E --> E1["Foucault\nEl poder como red productiva,\nno solo represiva"]
        E --> E2["Derrida\nDeconstrucción de los\ngrandes relatos legitimadores"]
        E --> E3["Lyotard\nIncredulidad hacia\nlas metanarrativas"]
        E --> E4["Contribución\nCuestiona fundamentos del poder,\nabre espacio para la diversidad"]
    end
