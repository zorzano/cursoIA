classDiagram
    GeneradorPasswords <|-- GPSencillo
    GeneradorPasswords <|-- GPassPhrases
    GeneradorPasswords: +generaPassword(int len)
    class GPSencillo{
          }
    class GPassPhrases{
    }
