```mermaid
flowchart TD
  Start([Start]) --> Input[/Call is_even_or_odd(number)/]
  Input --> IsInt{Is number an int?}
  IsInt -- No --> Invalid[/Return "Invalid input: Please enter an integer."/]
  Invalid --> End([End])
  IsInt -- Yes --> IsEven{number % 2 == 0?}
  IsEven -- Yes --> Even[/Return "Even"/]
  IsEven -- No --> Odd[/Return "Odd"/]
  Even --> End
  Odd --> End
```
