import 'package:flutter/material.dart';
import 'package:fluttertoast/fluttertoast.dart';


void main() {
  runApp(Homepage());
}

class Homepage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("MainActivity"),
        ),
        body: FirstScreen(),
      ),);}}

class FirstScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Center(
      child: ListView(
        children: [
          Card(
            shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(10)),
            child: ListTile(
              leading: CircleAvatar(
                  backgroundImage: AssetImage("assets/iconse.png")),
              title: Text("SDQ Contact"),
              trailing: Wrap(
                spacing: 10,
                children: [
                  Icon(Icons.messenger),
                  Icon(Icons.phone),
                ],
              ),
            ),
          ),
          Card(
            child: ListTile(
              leading: CircleAvatar(
                backgroundImage: NetworkImage(
                    "https://stickerly.pstatic.net/sticker_pack/nwkEm5fuu41RAku67F0h0Q/MK8T18/1/3726f55e-6116-4923-999d-97e97cf65bf3.png"),
              ),
              title: Text("Rider Anandhu"),
              trailing: Wrap(
                spacing: 10,
                children: [
                  Icon(Icons.messenger),
                  Icon(Icons.phone),
                ],
              ),
            ),
          ),
          Card(     
    child: ListTile(
              leading: CircleAvatar(
                backgroundImage: NetworkImage(
                    "https://stickerly.pstatic.net/sticker_pack/nwkEm5fuu41RAku67F0h0Q/MK8T18/1/8bee9ef9-7008-4c4f-94e9-38136b469cb7.png"),
              ),
              title: Text("Suni's SnackBar with Button"),
              trailing: Wrap(
                spacing: 10,
                children: [
                  Icon(Icons.messenger),
                  Icon(Icons.phone),
                ],
              ),
              onTap: () {
                final snackBar = SnackBar(
                  content: Text('Hey! This is a SnackBar message.'),
                  duration: Duration(seconds: 5),
                  action: SnackBarAction(
                    label: 'Undo',
                    onPressed: () {
                      // Some code to undo the change.
                    },
                  ),
                );
                ScaffoldMessenger.of(context).showSnackBar(snackBar);
              }),
          ),

          Card(
            child: ListTile(
              leading: CircleAvatar(
                backgroundImage: NetworkImage(
                    "https://static.toiimg.com/thumb/msid-65336414,width-800,height-600,resizemode-75,imgsize-9073,pt-32,y_pad-40/65336414.jpg"),
              ),
              title: Text("Raayappan with Toast"),
              trailing: Wrap(
                spacing: 10,
                children: [
                  Icon(Icons.messenger),
                  Icon(Icons.phone),
                ],
              ),
              onTap: () {
                Fluttertoast.showToast(
                    msg: "Click once again to open 'games 1'",
                    toastLength: Toast.LENGTH_SHORT,
                    gravity: ToastGravity.BOTTOM,
                    timeInSecForIosWeb: 1,
                    backgroundColor: Colors.black54,
                    textColor: Colors.white,
                    fontSize: 16.0);
              },
            ),
          ),
          
          Card(
            child: ListTile(
              leading: CircleAvatar(
                backgroundImage: NetworkImage(
                    "http://trollmememalayalam.in/wp-content/uploads/2017/11/Orithiri-Uluppu-Shankaradi-Meme-Nadodikkattu-Malayalam-Movie-Plain-Memes.jpg"),
              ),
              title: Text("Nihal Kutten with SnackBar only"),
              trailing: Wrap(
                spacing: 10,
                children: [
                  Icon(Icons.messenger),
                  Icon(Icons.phone),
                ],
              ),
              onTap: () {
                ScaffoldMessenger.of(context).showSnackBar(SnackBar(
                  content: Text('Hey! This is a SnackBar message.'),
                ),);
              },
            ),
          ),
        ],

      ),);
  }
}
