<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Community Volunteer Platform - Rate Experience</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #83a4d4, #b6fbff);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 2rem;
        }

        .container {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 600px;
            overflow: hidden;
        }

        .header {
            background-color: #f8f9fa;
            padding: 1.5rem;
            border-bottom: 1px solid #eee;
        }

        .header h2 {
            color: #2c3e50;
            margin-bottom: 0.5rem;
        }

        .header p {
            color: #7f8c8d;
            font-size: 0.9rem;
        }

        .opportunity-info {
            padding: 1.5rem;
            border-bottom: 1px solid #eee;
            display: flex;
            gap: 1rem;
        }

        .opportunity-image {
            width: 80px;
            height: 80px;
            background-color: #e9ecef;
            border-radius: 5px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #6c757d;
            font-size: 2rem;
        }

        .opportunity-details h3 {
            color: #2c3e50;
            margin-bottom: 0.5rem;
        }

        .opportunity-details p {
            color: #7f8c8d;
            font-size: 0.9rem;
        }

        .rating-section {
            padding: 1.5rem;
        }

        .rating-group {
            margin-bottom: 2rem;
        }

        .rating-group h4 {
            color: #2c3e50;
            margin-bottom: 1rem;
        }

        .stars {
            display: flex;
            gap: 0.5rem;
            margin-bottom: 1rem;
        }

        .star {
            font-size: 2rem;
            cursor: pointer;
            color: #ddd;
            transition: color 0.3s;
        }

        .star:hover,
        .star.active {
            color: #ffd700;
        }

        .rating-labels {
            display: flex;
            justify-content: space-between;
            color: #7f8c8d;
            font-size: 0.8rem;
        }

        .feedback-form {
            margin-top: 2rem;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            color: #2c3e50;
            font-weight: 500;
        }

        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            resize: vertical;
            min-height: 100px;
            font-size: 0.9rem;
        }

        .form-group textarea:focus {
            outline: none;
            border-color: #83a4d4;
        }

        .rating-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }

        .tag {
            padding: 0.5rem 1rem;
            background-color: #f8f9fa;
            border: 1px solid #ddd;
            border-radius: 20px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .tag:hover,
        .tag.active {
            background-color: #83a4d4;
            color: white;
            border-color: #83a4d4;
        }

        .submit-section {
            padding: 1.5rem;
            background-color: #f8f9fa;
            border-top: 1px solid #eee;
            text-align: right;
        }

        .submit-button {
            padding: 0.8rem 2rem;
            background-color: #83a4d4;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .submit-button:hover {
            background-color: #6b8cb3;
        }

        @media (max-width: 480px) {
            .opportunity-info {
                flex-direction: column;
                text-align: center;
            }

            .opportunity-image {
                margin: 0 auto;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h2>Rate Your Volunteer Experience</h2>
            <p>Your feedback helps improve our community</p>
        </div>

        <div class="opportunity-info">
            <div class="opportunity-image">🌟</div>
            <div class="opportunity-details">
                <h3>Youth Mentoring Program</h3>
                <p>Local Youth Center</p>
                <p>Volunteered on: January 15, 2025</p>
            </div>
        </div>

        <div class="rating-section">
            <div class="rating-group">
                <h4>Overall Experience</h4>
                <div class="stars">
                    <span class="star">★</span>
                    <span class="star">★</span>
                    <span class="star">★</span>
                    <span class="star">★</span>
                    <span class="star">★</span>
                </div>
                <div class="rating-labels">
                    <span>Poor</span>
                    <span>Excellent</span>
                </div>
            </div>

            <div class="rating-group">
                <h4>Organization & Communication</h4>
                <div class="stars">
                    <span class="star">★</span>
                    <span class="star">★</span>
                    <span class="star">★</span>
                    <span class="star">★</span>
                    <span class="star">★</span>
                </div>
            </div>

            <div class="feedback-form">
                <div class="form-group">
                    <label>What did you like about this experience?</label>
                    <div class="rating-tags">
                        <span class="tag">Well Organized</span>
                        <span class="tag">Friendly Staff</span>
                        <span class="tag">Meaningful Work</span>
                        <span class="tag">Good Training</span>
                        <span class="tag">Flexible Hours</span>
                        <span class="tag">Clear Instructions</span>
                    </div>
                </div>

                <div class="form-group">
                    <label>Share your detailed feedback</label>
                    <textarea placeholder="Tell us about your experience..."></textarea>
                </div>
            </div>
        </div>

        <div class="submit-section">
            <button class="submit-button">Submit Review</button>
        </div>
    </div>
</body>
</html>
