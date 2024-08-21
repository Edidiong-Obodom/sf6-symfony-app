# PHP Symfony

## Setting Up the Project

<ol>
  <li>Navigate to the <code>htdocs</code> directory in XAMPP:</li>
  <ul>
    <li>Open the CMD terminal (type <code>cmd</code> and press Enter).</li>
    <li>Run the following command to create a new Symfony project:</li>
  </ul>
  <pre><code>symfony new project_name</code></pre>

  <li>Change into the project directory:</li>
  <pre><code>cd project_name</code></pre>

  <li>Open the project in Visual Studio Code:</li>
  <pre><code>code .</code></pre>

  <li>Start the Symfony server:</li>
  <pre><code>symfony server:start</code></pre>
  <li>Install the ORM Pack for database management:</li>
  <pre><code>composer req symfony/orm-pack</code></pre>

  <li>Install the Maker Bundle for generating code (e.g., entities):</li>
  <pre><code>composer req symfony/maker-bundle</code></pre>

  <li>Install Twig, the templating engine for the Symfony framework:</li>
  <pre><code>composer req twig</code></pre>

  <li>Generate a new controller:</li>
  <pre><code>php bin/console make:controller</code></pre>

  <li>Generate a new entity:</li>
  <pre><code>php bin/console make:entity</code></pre>

  <li>Create a migration:</li>
  <pre><code>php bin/console make:migration</code></pre>

  <li>Apply the migration to the database:</li>
  <pre><code>php bin/console doctrine:migrations:migrate</code></pre>

  <li>Install Form and Validator components:</li>
  <pre><code>composer req form validator</code></pre>

  <li>Create a form:</li>
  <pre><code>php bin/console make:form</code></pre>
</ol>
