# IMAD-PRACTICUM
Mutanganedzwa Tshamano
ST10439899


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

    
