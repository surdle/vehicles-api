# Simple Motorcyle API in Deno 🦕

This is a simple API built with Deno that provides information about motorcycles based on their manufacturing year.

## Available Routes

- GET /api/motorcycles/:year

    Retrieves information about motorcycles manufactured in the specified year.

    Example: `/api/motorcycles/2022`

    Response:
    ```json
    {
        "make": "DUCATI",
        "models": [
            "1098S",
            "1199",
            "500 PANTAH",
            "M900",
            "M900/900 S",
            "MH900E",
            "MTS 620",
            "SUPER SPORT",
            "SUPER SPORT 1000 DS"
        ]
    }
    ```

## Getting Started

To run the API, make sure you have Deno installed on your machine. Then, follow these steps:

1. Clone the repository:

        ```
        git clone https://github.com/your-username/simpleMotorcyleAPI.git
        ```

2. Navigate to the project directory:

        ```
        cd simpleMotorcyleAPI
        ```

3. Run the API:

        ```
        deno run --allow-net main.ts
        ```

        The API will start running on `http://localhost:8000`.

