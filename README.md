### Hi there 👋
<!--
CREATE TABLE default.person (
  first_name STRING,
  last_name STRING,
  gender STRING,
  location STRING,
  blurb STRING,
  skills ARRAY,
  interests ARRAY,
  urls ARRAY
);
-->
```sql
-- Bootstrapping Simon Engelbert

INSERT INTO person
  (first_name,
  last_name,
  gender,
  location,
  blurb,
  skills,
  interests)
VALUES      
  ('Simon',
  'Engelbert',
  'Male',
  'Colorado',
  'Data & DevOps leader with expertise in innovation, complex problem-solving, and building high-performing engineering teams',
  ARRAY_CONSTRUCT
    ('Leadership',
    'Data',
    'DevOps',
    'Software Engineering'),
  ARRAY_CONSTRUCT
    ('Linux',
    'Android',
    'AI',
    'DeFi',
    'Fitness',
    'Food'),
  ARRAY_CONSTRUCT
    ('https://simonengelbert.com/',
    'https://www.linkedin.com/in/simonengelbert/')  
  );
```
