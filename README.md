# resturante-menu

import 'package:flutter/material.dart';
// ID: C119560
//Name : Abdikaafi mohamed Hassan
void main() {
  runApp(MaterialApp(
    debugShowCheckedModeBanner: false,
    home: Scaffold(
      body: Column(
        children: [
          Container(
            child: Card(
              shape: RoundedRectangleBorder(
                  borderRadius: BorderRadius.circular(15)),
              margin: EdgeInsets.all(10.0),
              color: Colors.deepOrange,
              child: Row(
                children: <Widget>[
                  //   Image.asset('assets/img/pizz.png')
                  Image(
                    image: AssetImage('assets/img/chees.jpg'),
                    width: 100.0,
                    height: 100.0,
                  ),
                  SizedBox(width: 20.0),
                  Text(
                    'Chees Pizz ',
                    style: TextStyle(
                        fontWeight: FontWeight.bold,
                        color: Colors.white,
                        fontSize: 30.0),
                  )
                ],
              ),
            ),
          ),
          Container(
            child: Card(
              shape: RoundedRectangleBorder(
                  borderRadius: BorderRadius.circular(15)),
              margin: EdgeInsets.all(10.0),
              color: Colors.deepOrange,
              child: Row(
                children: <Widget>[
                  //   Image.asset('assets/img/pizz.png')
                  Image(
                    image: AssetImage('assets/img/freis.jpg'),
                    width: 100.0,
                    height: 100.0,
                  ),
                  SizedBox(width: 20.0),
                  Text(
                    'Box of Freis ',
                    style: TextStyle(
                        fontWeight: FontWeight.bold,
                        color: Colors.white,
                        fontSize: 30.0),
                  )
                ],
              ),
            ),
          ),
          Container(
            child: Card(
              shape: RoundedRectangleBorder(
                  borderRadius: BorderRadius.circular(15)),
              margin: EdgeInsets.all(10.0),
              color: Colors.deepOrange,
              child: Row(
                children: <Widget>[
                  //   Image.asset('assets/img/pizz.png')
                  Image(
                    image: AssetImage('assets/img/pizz1.jpg'),
                    width: 100.0,
                    height: 100.0,
                  ),
                  SizedBox(width: 20.0),
                  Text(
                    'Vigtable Pizz ',
                    style: TextStyle(
                        fontWeight: FontWeight.bold,
                        color: Colors.white,
                        fontSize: 30.0),
                  )
                ],
              ),
            ),
          )
        ],
      ),
    ),
  ));
}






