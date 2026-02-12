# CS506-FinalProject
Description of Project:
    
    Project Topic:
        This project is focused on identifying the key lifestyle contributors among college students that impact exam performance.

    Project Timeline Planned:
        Feb 15th - 21st
            Create Google Form for gathering local information for future testing, release form upon completion. Work out issues with designing the form, gathering the correct data, and ensuring ethical and reliable data sourcing.

        Feb 22nd - 28th:
            Begin cleaning the synthetic data alongside what has come in from the polling data (polling data cleaning will become a weekly task). In addition, begin identifying what features of the data would be best to highlight in the project.

        March 1st - 7th:
            Research data modeling concepts to discover what methods would fit best to achieve the goal of the project. Create a solid idea of the top 3-5 modeling concepts and begin working with them.

        Spring Break:
            Not planning on doing much work over the break. If extra work needs to be done with gathering surveys or preparing for future project steps, I will take some time to complete such work.

        March 15th - 21st:
            Not exactly sure when check-ins will be, but assume they will occur following Spring break. Prep documentation on current project progress to prepare for the check-in.

        March 22nd - 28th:
            Continue working with the modeling concepts, but begin to streamline on 3 modeling concepts to be used and mentioned in the project. Only one will be selected, but 2 will be included in order to provide evidence of alternative methods being explored.

        March 29th - April 4th:
            By this point, a data modeling concept should be selected as the best fit for the project. Begin heavy usage of the method on both the synthetic data and the real data.

        April 5th - 11th:
            Continue developing model training until testing becomes reliable.

        April 12th - 18th:
            Complete training/testing work with the model and begin to use results for visualization. Begin documenting results and findings.

        April 19th - 25th:
            Begin work on presentation resources. Repo should be nearly done.

        April 26th - 30th:
            Make final adjustments to repo if necessary. In addition, make final adjustments to presentation resources and begin to practice presenting.

        May 1st:
            Assignment is due. If due at 11:59, ensure the presentation and the repo are updated with all information. Continue to practice presenting.

Goals of the Project:
    
    1. Identify key lifestyle contributors to university student exam performance (planning on creating a system to rank what has the greatest impact on student performance)

    2. Develop a unit scaling system in which student performance is explained by lifestyle factors (ex: X extra hours of sleep increases scoring by 1)

    3. Present solutions to correct lifestyle choices to increase general student performances (while not measurable, this goal exists to give the project a purpose outside of schoolwork)

Data Collection Plans:
    
    Potential Data Sources:
        1. Kaggle: https://www.kaggle.com/datasets/lainguyn123/student-performance-factors
        
        2. Kaggle: https://www.kaggle.com/datasets/algozee/student 
        
        3. Polling: students will fill out a form with questions that will gather data similar to the data within the kaggle datasets. This form is yet to be developed.

    Data Collection Method Explained:
        The two kaggles contain sythetic data, which is usable for training and testing as it is based on real world information, but not entirely reliable. Hence is why I am looking to gain real data from students on campus through polling data. I plan to create a form to gather information from as many students as possible in order to have more realistic data to test against my model. I plan for the polling data to be as general as possible with responses from students of different classes, majors, and backgrounds.


Testing Plan:
    
    1. The first kaggle will be the main source of training information, with a planned 80/20 split of training to testing data

    2. The second kaggle will be tested against the model developed by the first with the factors that are present in both datasets. With the possibility of training on some of the data if testing proves to be inaccurate

    3. The final kaggle model product will be tested against the data from the polls. If found to be inaccurate, further training using the real data will be implemented, but I am training to restrain the amount of data to train on as much as possible as this will be the smallest dataset.