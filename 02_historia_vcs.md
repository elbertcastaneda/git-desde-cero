1. Gestión de la configuración _del software_ (CM, SCM).
    1. **master/trunk** (La ultima version funcional)
        1. CI (PR, TDD, Test Coverage)
        1. CD (QA Automation)
    1. **ramas/branches** (Areas de trabajo)
        1. Basada en Personas.
        1. Rama por caracteristica (Feature Branch, Brand per Issue, etc).
        1. Rama para pruebas de concepto
        1. etc (Devel, Preproduccion, etc)
    1. **Etiquetas/tags** (Liberaciones)
        1. Linea Base (BaseLines)
        1. Versiones estables
        1. Solo lectura (Para compilar/ejecutar)
        ![02_scm.png](quiver-image-url/526AA39BD75D9E88FB60401FD7080A20.png =620x597)
1. Primera Generación (Enfocada en archivos).
    1. Bloqueo de archivos.
    1. Solo para un solo usuario.
    1. RCS, SCCS, La primera version SourceSafe
1. Segunda Generación (Centralizada, cliente-servidor)
    1. CVS (Bloqueo de archivos).
    1. SourceSafe (Bloqueo de archivos).
    1. Subversion, TFS (Unir antes de enviar).
1. Tercera Generación (Repartida o descentralizada, changeset)
    1. **Git.**
    1. Mercurial.
    1. Bazar.