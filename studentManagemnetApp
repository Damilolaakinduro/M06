import javafx.application.Application;
import javafx.scene.Scene;
import javafx.scene.control.*;
import javafx.scene.layout.*;
import javafx.stage.Stage;

public class StudentManagementApp extends Application {

    public static void main(String[] args) {
        launch(args);
    }

    @Override
    public void start(Stage primaryStage) {
        primaryStage.setTitle("Student Management System");

        // Create a login window
        BorderPane loginLayout = new BorderPane();
        Scene loginScene = new Scene(loginLayout, 400, 200);
        
        // Add login controls (e.g., username and password fields)
        TextField usernameField = new TextField();
        PasswordField passwordField = new PasswordField();
        Button loginButton = new Button("Login");

        // Create event handlers for loginButton
        loginButton.setOnAction(e -> {
            String username = usernameField.getText();
            String password = passwordField.getText();
            // Perform authentication and navigate to the main dashboard if successful
            // Display an error message if authentication fails
        });

        // Add controls to the login layout
        VBox loginBox = new VBox(10);
        loginBox.getChildren().addAll(
            new Label("Username:"),
            usernameField,
            new Label("Password:"),
            passwordField,
            loginButton
        );
        loginLayout.setCenter(loginBox);

        // Show the login window
        primaryStage.setScene(loginScene);
        primaryStage.show();
    }
}



import javafx.scene.Scene;
import javafx.scene.control.*;
import javafx.scene.layout.*;
import javafx.stage.Stage;

public class Dashboard {

    public static void showDashboard(Stage primaryStage) {
        primaryStage.setTitle("Student Dashboard");

        // Create a dashboard window
        BorderPane dashboardLayout = new BorderPane();
        Scene dashboardScene = new Scene(dashboardLayout, 800, 600);

        // Add dashboard controls (e.g., student list, course enrollment)
        ListView<String> studentList = new ListView<>();
        Button enrollButton = new Button("Enroll in Course");

        // Create event handlers for enrollButton and studentList
        enrollButton.setOnAction(e -> {
            // Handle course enrollment for the selected student
        });

        // Add controls to the dashboard layout
        VBox dashboardBox = new VBox(10);
        dashboardBox.getChildren().addAll(
            new Label("Student List:"),
            studentList,
            enrollButton
        );
        dashboardLayout.setCenter(dashboardBox);

        // Show the dashboard window
        primaryStage.setScene(dashboardScene);
    }
}
