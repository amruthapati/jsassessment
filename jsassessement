/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/
// create a variable to hold your NFT's
let NFTContainer = [];
// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.

function mintNFT(name ,place , eyecolor , height , birthdate) {
    let NFT = {
        name: name,
        place: place,
        eyecolor: eyecolor,
        height: height,
        birthdate: birthdate ,
    }
    NFTContainer.push(NFT);
   console.log("Minted "+ name);

}
// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs () {
    for (let i = 0; i < NFTContainer.length; i++) {
        console.log("Name: " + NFTContainer[i].name);
        console.log("place: " + NFTContainer[i].place);
        console.log("eyecolor: " + NFTContainer[i].eyecolor);
        console.log("height: " + NFTContainer[i].height);
        console.log("birthdate: " + NFTContainer[i].birthdate);
    }
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {console.log("total number of NFTs are - :" + NFTContainer.length);

}
// call your functions below this line
mintNFT("Alexa", "Banglore", "Black","5.2ft"," 27-09-2001");
mintNFT("George", "Manglore", "Grey","5.8ft"," 09-10-2000");
mintNFT("Lara", "Mumbai", "Brown","5.7ft","17-11-2002");
mintNFT("Jerry", "Hyderabad", "Blue"," 6ft"," 11-07-2000");
listNFTs();
getTotalSupply();
