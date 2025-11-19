```mermaid
flowchart TD
    Start([Start])
    Input[/Call is_even_or_odd(number)/]
    Check{number % 2 == 0 ?}
    Even[/Return "Even"/]
    Odd[/Return "Odd"/]
    End([End])

    Start --> Input --> Check
    Check -- Yes --> Even --> End
    Check -- No --> Odd --> End
```
