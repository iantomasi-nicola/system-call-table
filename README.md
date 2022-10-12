# System Call Table

Created by Nicola Iantomasi

| Name      | %eax |       %ebx        |  %ecx  | %edx  |
|-----------|:----:|:-----------------:|:------:|:-----:|
| sys_exit  |  1   | "Return zero" (int) |   -    |   -   |
| sys_write |  4   |        $12        |        |       |