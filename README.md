# galaxypay-sdk-android
##SDK Android native SDK using kotlin, auto binding with MVVM architech

###MVVM architech:
![mvvm-arch.png](gitreadme/mvvm-arch.png)

##Structure

-------
![gpsdk-mvvm-arch.png](gitreadme/gpsdk-mvvm-arch.png)

- [ ] **data** (MODEL):  It contains all the data accessing and manipulating components. (Bussiness Logic and Data)
    - api (service): service classes
    - model (data): data model
    - repository: bussiness classes
- [ ] **ui** (VIEW): View classes along with their corresponding with ViewModel.
  - view: page/ UI class include activity and fragment
    - activity
      - ...
      - ...
    - fragment
      - ...
      - ...
  - base: common view/ common layout
- [ ] **viewModel** (VIEW-MODEL): ViewModel classes (Presention/controller classes)
  - factory: ViewModelFactory classes
  - ...
- utils: Utility classes.
- enums: Enum classes
---------

###MVVM Details:
Kotlin + MVVM + Databinding = Easy maintainable and efficient code

![mvvm-flow.png](gitreadme/mvvm-flow.png)

In MVVM,

- **Model** — contains all the data classes, database classes, API and repository
- **View** — is the UI part that represents the current state of information that is visible to the user.
- **ViewModel** — it contains the data required in the View and translates the data which is stored in Model which then can be present inside a View. ViewModel and View are connected through Databinding and the observable Livedata.