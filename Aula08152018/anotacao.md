Campos tipos de datas
===

> CURRENT_DATE()
> select current_date();

> DATE_FORMAT()
> seelct date_format(curdate() , '%d/%m/%y);

> EXTRACT() 
> select extract( day from curdate() as dia, month from curdate() as mês, year from curdate() as ano);

> DATE_ADD()
>select date_add('2018-08-15', interval 30 days);

> DATEDIFF()
> select datediff ('2018-08-15', '2018-12-01');

> PERIOD_DIFF()
> select period_diff('201212', '201204');

> DAYOFYEAR()
> select dayofyear('2018-08-15');