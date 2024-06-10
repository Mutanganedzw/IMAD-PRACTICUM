# IMAD-PRACTICUM
Mutanganedzwa Tshamano
ST10439899

https://github.com/Mutanganedzw/IMAD-PRACTICUM

The application can be used to provide users with current weather conditions such as temperature, humidity, and wind. The app can also help users with forecasting, which will offer weather forecasts for the upcoming hours, days, and even weeks, which will help users plan their activities accordingly without the disturbance of the weather.
There will also be a platform which will help[ with usere interface and experience.
Which will also deliver a visually appealing and user friendly interface to show weather information in an easy and understyandable format.
Pseudocode:

START

//DECLARATION

class MainActivity : AppCompatActivity
{

    // ViewModel:
    
    var weatherViewModel: WeatherViewModel
    
    var adapter: WeatherAdapter

    funtion

    onCreate(savedInstanceState: Bundle) {

    super.oncreate(savedInstanceState)

        //initialize ViewModel
        weatherViewModel = 

        ViewModelProvider(this).get(WeatherViewModel::class.java)

        // Retrieve selected day data
        
        val selectedDay = 

        intent.getExtra("selected_day") as WeatherDay

            //Update with selected day data

            findViewById<TextView>(R.id.condition).

            text = selectedDay.condition

            }

            END

 ![Capture](https://github.com/Mutanganedzw/IMAD-PRACTICUM/assets/166540448/2e043626-b618-4090-9cad-8a3550f19e0d)
           
![sft](https://github.com/Mutanganedzw/IMAD-PRACTICUM/assets/166540448/81812a08-a070-4644-af6b-e3c78233ed5c)

![Cap](https://github.com/Mutanganedzw/IMAD-PRACTICUM/assets/166540448/046e77ed-5ab5-45fa-8c9c-fcd1c8b34bc6)
    
![Captu](https://github.com/Mutanganedzw/IMAD-PRACTICUM/assets/166540448/1c1ca7c4-835d-4c83-8bc5-7af285e6f465)

![JV](https://github.com/Mutanganedzw/IMAD-PRACTICUM/assets/166540448/666c599e-c587-48c5-8e99-b4fe9296dfba)

![HTZ](https://github.com/Mutanganedzw/IMAD-PRACTICUM/assets/166540448/e0c592e1-b772-4832-8998-00c008d2fe70)
