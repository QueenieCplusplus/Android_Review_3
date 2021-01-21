# Android_Review_3
Navigation 

1. create new project, select default layout called Navigation Drawer Layout stype choices from on of them.

        // activity_main.xml
        
           package com.example.android.katesapp
           
           [default modules]
           import androidx.appcompat.app.AppCompatActivity
           import android.os.Bundle
           
           [databinding modules]
           import androidx.databinding.DataBindingUtil
           import com.example.andorid.katesapp.databinding.ActivityMainBinding
           
           [drawerlayout modules]
           import androidx.drawerlayout.widget.Drawerlayout
           
           [naviagtion modules]
           import androidx.navigation.findNavController //a Public Method to be called
           import androidx.navigation.ui.NavigationUI
           
           class MainActivity: AppCompatActivity(){
           
              override fun onCreate(){
              
              
              }
              
           
              /*override fun onSupportNavigateUp(): Boolean {
              
                val navController = findNavController(R.id.myNavHostFragment)
                return navController.navigateUp(appBarConfiguration) || super.onSupportNavigateUp()
               
              }*/
              
              override fun onSupportNavigateUp(): Boolean {
              
                 val navController = this.findNavController(R.id.myNavHostFragment)
                 return Naviagtion
              
              }
           
           }
           
        
         
        // nav_header.xml
        
        <?xml encoding="utf-8"?>
        <androidx.constraintlayout.widget.ConstraintLayout
          android:id="@id/navHeader"
        >
        
          
        
        
        </androidx.constraintlayout.widget.ConstraintLayout>
