# ReNoVa  

### Empowering Sustainability Through Furniture Restoration  

ReNoVa is an innovative platform designed to reduce furniture waste by enabling individuals to restore and repurpose old furniture. Using advanced image-processing tools, ReNoVa allows users to visualize restoration by cleaning up stains, scratches, and imperfections digitally before taking action. By promoting a circular economy, ReNoVa helps reduce environmental waste and fosters a community dedicated to sustainability.  

---  

## Features  

- **Image Restoration Tools:**  
  Advanced image-processing powered by OpenCV to digitally clean and restore furniture visuals.  

- **Recommendation System:**  
  Personalized furniture suggestions using Scikit-learn and Pandas for intelligent recommendations.  

- **Image Search Engine:**  
  Seamlessly find similar furniture using a PyTorch-based image search engine.  

- **Circular Economy Tools:**  
  Donate, sell, or reuse restored furniture to minimize waste and contribute to sustainable living.  

- **Swagger API Documentation:**  
  Explore the API at [http://13.49.145.211:3000/swagger/index.html](http://13.49.145.211:3000/swagger/index.html).  

---  

## Tech Stack  

- **Frontend:** Next.js, Tailwind CSS  
- **Backend:** Golang  
- **Image Processing:** OpenCV, PyTorch  
- **Recommendation System:** Scikit-learn, Pandas  
- **Database:** MySQL  
- **Hosting:** AWS (Amazon Web Services)  

---  

## Getting Started  

### Prerequisites  

- Node.js >= 16.x  
- npm >= 8.x  
- Go >= 1.20  
- MySQL instance  

### Installation  

#### Frontend  

1. Navigate to the frontend directory:  
   ```bash  
   cd frontend  
   ```  

2. Install dependencies:  
   ```bash  
   npm install  
   ```  

3. Run the development server:  
   ```bash  
   npm run dev  
   ```  

#### Backend  

1. Navigate to the backend directory:  
   ```bash  
   cd backend  
   ```  

2. Install Go dependencies:  
   ```bash  
   go mod tidy  
   ```  

3. Set up environment variables:  
   Create a `.env` file in the `backend` directory and include:  
   ```env  
   DB_USER=<your-mysql-user>  
   DB_PASS=<your-mysql-password>  
   DB_HOST=<your-mysql-host>  
   DB_PORT=3306  
   DB_NAME=renova  
   AWS_ACCESS_KEY=<your-aws-access-key>  
   AWS_SECRET_KEY=<your-aws-secret-key>  
   ```  

4. Run the backend server:  
   ```bash  
   go run main.go  
   ```  

---  

## Contributing  

We welcome contributions to enhance ReNoVa!  

1. Fork this repository.  
2. Create a feature branch (`git checkout -b feature/your-feature-name`).  
3. Commit your changes (`git commit -m "Add a new feature"`).  
4. Push the branch (`git push origin feature/your-feature-name`).  
5. Open a Pull Request on GitHub.  

Please ensure your code adheres to our [Code of Conduct](CODE_OF_CONDUCT.md).  

---  

## API Documentation  

Explore our Swagger API documentation for backend routes:  
[http://13.49.145.211:3000/swagger/index.html](http://13.49.145.211:3000/swagger/index.html).  

---  

## License  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

---  

## Acknowledgments  

ReNoVa started as a project for the **Huawei and BTK Coding Marathon 2024**, where it earned **4th place**. With further improvements and enhancements, the project advanced to the **Huawei Spark Infinity 2024 Europe** competition and achieved an incredible **2nd place**, showcasing its potential and impact on sustainability and innovation.

---  

## Contact  

For questions or more information, contact us at:   
- **GitHub Issues:** [Issues Page](https://github.com/<organization-name>/renova/issues)  
