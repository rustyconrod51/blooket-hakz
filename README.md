// Function to simulate the Blooket crypto hack
function blooketCryptoHack() {
  // Ask the user how many credits they want
  let creditsWanted = prompt("How many credits would you like?");

  // Validate the input
  while (isNaN(creditsWanted) || creditsWanted < 0) {
    creditsWanted = prompt("Invalid input. Please enter a non-negative whole number.");
  }

  // Simulate the hack
  console.log("Hacking into Blooket's system...");
  console.log("Generating crypto credits...");
  console.log("Transferring credits to your account...");

  // Display the result
  console.log(`Success! You now have ${creditsWanted} credits.`);
  alert(`Success! You now have ${creditsWanted} credits.`);
}

// Call the function
blooketCryptoHack();
