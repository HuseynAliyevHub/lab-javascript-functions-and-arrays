good job!

we should always protect our functions just in case they receive a null or an empty array, luckily for us it's really simple to do it,
in the first line of each function that expects an object or an array we should write something like this:

for example in findLongestWords function:

  if (!words || !words.length) return null;
