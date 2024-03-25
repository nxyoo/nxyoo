<?php 

$_POST['id'] = 35;
array_splice($_POST, $_POST['id']);

    function addMessageIfValueIsEmpty(array $errors, string $field): array
    {
        if (empty($_POST[$field])) {
            $errors[$field][] = sprintf('Le champ "%s" doit être renseigné.', $field);
        }

        return $errors;
    }

    function displayErrors(array $errors, string $field): void
    {

        if (isset($errors[$field])) {
            foreach ($errors[$field] as $error) {
                echo '<p class="error">' . $error . '</p>';
            }
        }
    }

    // Si formulaire soumis et données transmises :
    // Méthode = POST
    // Données de POST non vide. empty($_POST) : si vide = true : sinon false)
    $errors = [];
    if ($_SERVER['REQUEST_METHOD'] === 'POST' && empty($_POST) === false) {

        // Ok des données sont transmises.
        
        $errors = addMessageIfValueIsEmpty($errors, 'first_name');
        $errors = addMessageIfValueIsEmpty($errors, 'last_name');
        $errors = addMessageIfValueIsEmpty($errors, 'email');
        $errors = addMessageIfValueIsEmpty($errors, 'profession');
        $errors = addMessageIfValueIsEmpty($errors, 'interest');
        $errors = addMessageIfValueIsEmpty($errors, 'agreeNewsletter');

        // Vérification de l'email
        // Il faut pour cela que l'email soit saisi.
        if (!empty($_POST['email'])) {
            if (!filter_var($_POST['email'], FILTER_VALIDATE_EMAIL)) {
            	$errors['email'][] = 'Le champ "email" n\'est pas valide.';
            }
            
        }

    }

    
    if ($_SERVER["REQUEST_METHOD"] === "POST" && !empty($_POST['first_name'] && !empty($_POST['last_name']) && !empty($_POST['email']) && !empty($_POST['profession'] && !empty($_POST['agreeNewsletter']) == true )) ) {
        $first_name = htmlspecialchars(htmlentities($_POST['first_name']));
        $last_name = htmlspecialchars(htmlentities($_POST['last_name']));
        $email = htmlspecialchars(htmlentities($_POST['email']));
        $profession = htmlspecialchars(htmlentities($_POST['profession']));
        $agreeNewsletter = htmlspecialchars(htmlentities($_POST['agreeNewsletter']));
        implode($_POST);
        $_POST = json_encode($_POST);
    }
        var_dump($_POST);
    

?> 

<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
   <script src="https://cdn.tailwindcss.com"></script>
     <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primary: '#000',
            'primary-foreground': '#FFF',
          }
        }
      }
    }
  </script>
  <title>Subscribe to your newsletter</title>
</head>
<body>
<div class="mx-auto max-w-2xl space-y-8">
  <div class="space-y-2 !mt-8">
    <h1 class="text-3xl font-bold">Subscribe to your newsletter</h1>
    <p class="text-gray-500 dark:text-gray-400">Enter your information to get in touch</p>
  </div>
  <form class="space-y-4" action="http://51.91.108.32/registrations" method="post">
    <div class="grid grid-cols-2 gap-4">
      <div class="space-y-2">
        <label
          class="text-sm font-medium leading-none peer-disabled:cursor-not-allowed peer-disabled:opacity-70"
          for="first-name">
          First name<span class="text-red-500">*</span>
        </label>
        <input
          class="flex h-10 w-full rounded-md border border-input bg-background px-3 py-2 text-sm ring-offset-background file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50"
          id="first_name"
          name="first_name"
          placeholder="Enter your first name"
        />
        <?php displayErrors($errors, 'first_name'); ?>
      </div>
      <div class="space-y-2">
        <label
          class="text-sm font-medium leading-none peer-disabled:cursor-not-allowed peer-disabled:opacity-70"
          for="last_name"
          name="last_name"
        >
          Last name<span class="text-red-500">*</span>
        </label>
        <input
          class="flex h-10 w-full rounded-md border border-input bg-background px-3 py-2 text-sm ring-offset-background file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50"
          id="last_name"
          name="last_name"
          placeholder="Enter your last name"
        />
        <?php displayErrors($errors, 'last_name'); ?>
      </div>
    </div>
    <div class="space-y-2">
      <label
        class="text-sm font-medium leading-none peer-disabled:cursor-not-allowed peer-disabled:opacity-70"
        for="email"
        name="email"
      >
        Email<span class="text-red-500">*</span>
      </label>
      <input
        class="flex h-10 w-full rounded-md border border-input bg-background px-3 py-2 text-sm ring-offset-background file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50"
        id="email"
        name="email"
        placeholder="Enter your email"
        type="email"
      />
      <?php displayErrors($errors, 'email'); ?>
    </div>
    <div class="space-y-2">
      <label
        class="text-sm font-medium leading-none peer-disabled:cursor-not-allowed peer-disabled:opacity-70"
        for="profession"
        name="profession"
      >
        Profession<span class="text-red-500">*</span>
      </label>
      <input
        class="flex h-10 w-full rounded-md border border-input bg-background px-3 py-2 text-sm ring-offset-background file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50"
        id="profession"
        name="profession"
        placeholder="Enter your profession"
      />
      <?php displayErrors($errors, 'profession'); ?>
    </div>
    <div class="space-y-2">
      <span class="block text-sm font-medium text-gray-900 dark:text-gray-100">Interests</span>
      <div class="grid grid-cols-2 gap-4">
        <div class="flex items-center space-x-2">
          <input
            type="checkbox"
            value="Machine Learning"
            class="peer h-4 w-4 shrink-0 rounded-sm border border-primary ring-offset-background focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50 data-[state=checked]:bg-primary data-[state=checked]:text-primary-foreground"
            id="machine-learning"
          />
          <label
            class="peer-disabled:cursor-not-allowed peer-disabled:opacity-70 text-sm font-medium"
            for="machine-learning"
            name="interest"
          >
            Machine Learning
          </label>
        </div>
        <div class="flex items-center space-x-2">
          <input
            type="checkbox"
            role="checkbox"
            value="Product Design"
            class="peer h-4 w-4 shrink-0 rounded-sm border border-primary ring-offset-background focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50 data-[state=checked]:bg-primary data-[state=checked]:text-primary-foreground"
            id="product-design"
            name="interest"
          />
          <label
            class="peer-disabled:cursor-not-allowed peer-disabled:opacity-70 text-sm font-medium"
            for="product-design"
            name="interest"
          >
            Product Design
          </label>
        </div>
        <div class="flex items-center space-x-2">
          <input
            type="checkbox"
            role="checkbox"
            value="Web Development"
            class="peer h-4 w-4 shrink-0 rounded-sm border border-primary ring-offset-background focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50 data-[state=checked]:bg-primary data-[state=checked]:text-primary-foreground"
            id="web-development"
            name="interest"
          />
          <label
            class="peer-disabled:cursor-not-allowed peer-disabled:opacity-70 text-sm font-medium"
            for="web-development"
            name="interest"
          >
            Web Development
          </label>
        </div>
        <div class="flex items-center space-x-2">
          <input
            type="checkbox"
            name="interest"
            value="Crypto"
            class="peer h-4 w-4 shrink-0 rounded-sm border border-primary ring-offset-background focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50 data-[state=checked]:bg-primary data-[state=checked]:text-primary-foreground"
            id="crypto"
          />
          <label class="peer-disabled:cursor-not-allowed peer-disabled:opacity-70 text-sm font-medium" for="crypto">
            Crypto
          </label>
        </div>
      </div>
    </div>
    <div class="space-y-2 !mt-8">
      <div class="flex items-center space-x-2">
        <input
          type="checkbox"
          value="agreeNewsletter"
          name="agreeNewsletter"
          class="peer h-4 w-4 shrink-0 rounded-sm border border-primary ring-offset-background focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50 data-[state=checked]:bg-primary data-[state=checked]:text-primary-foreground"
          id="agreeNewsletter"
        />
        <label class="peer-disabled:cursor-not-allowed peer-disabled:opacity-70 text-sm font-medium" for="policy">
          By subscribing to the newsletter, you confirm that you have read our policy on the protection of your
          personal data. You can unsubscribe at any time by clicking on the link at the bottom of the newsletter or
          by making a simple request.<span class="text-red-500">*</span>
        </label>
      </div>
      <?php displayErrors($errors, 'agreeNewsletter'); ?>
    </div>
    <button
      class="inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 bg-primary text-primary-foreground hover:bg-primary/90 h-10 px-4 py-2"
      type="submit" value="submit" id="submit" name="submit"
    >
      Submit
    </button>
  </div>
</div>
</body>
</html>

