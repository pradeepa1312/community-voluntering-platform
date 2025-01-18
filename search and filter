<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Community Volunteer Platform - Search Opportunities</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f5f7fa;
            min-height: 100vh;
            padding: 2rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .header {
            margin-bottom: 2rem;
        }

        .header h1 {
            color: #2c3e50;
            margin-bottom: 0.5rem;
            font-size: 2rem;
        }

        .header p {
            color: #7f8c8d;
        }

        .search-section {
            background-color: white;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 2rem;
        }

        .search-bar {
            display: flex;
            gap: 1rem;
            margin-bottom: 1.5rem;
        }

        .search-input {
            flex: 1;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }

        .search-button {
            padding: 0.8rem 1.5rem;
            background-color: #83a4d4;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .search-button:hover {
            background-color: #6b8cb3;
        }

        .filters {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
        }

        .filter-group {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }

        .filter-group label {
            font-weight: 500;
            color: #2c3e50;
        }

        .filter-group select {
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 0.9rem;
            background-color: white;
        }

        .results {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }

        .opportunity-card {
            background-color: white;
            border-radius: 10px;
            padding: 1.5rem;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .opportunity-card:hover {
            transform: translateY(-5px);
        }

        .opportunity-card h3 {
            color: #2c3e50;
            margin-bottom: 0.5rem;
            font-size: 1.2rem;
        }

        .organization {
            color: #7f8c8d;
            margin-bottom: 1rem;
            font-size: 0.9rem;
        }

        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-bottom: 1rem;
        }

        .tag {
            background-color: #e8f0fe;
            color: #83a4d4;
            padding: 0.3rem 0.8rem;
            border-radius: 15px;
            font-size: 0.8rem;
        }

        .card-footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 1rem;
            padding-top: 1rem;
            border-top: 1px solid #eee;
        }

        .location {
            color: #7f8c8d;
            font-size: 0.9rem;
        }

        .apply-button {
            padding: 0.5rem 1rem;
            background-color: #83a4d4;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .apply-button:hover {
            background-color: #6b8cb3;
        }

        @media (max-width: 768px) {
            .search-bar {
                flex-direction: column;
            }
            
            .filters {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Find Volunteer Opportunities</h1>
            <p>Search and filter through available opportunities in your community</p>
        </div>

        <div class="search-section">
            <div class="search-bar">
                <input type="text" class="search-input" placeholder="Search by keyword, organization, or location">
                <button class="search-button">Search</button>
            </div>

            <div class="filters">
                <div class="filter-group">
                    <label for="category">Category</label>
                    <select id="category">
                        <option value="">All Categories</option>
                        <option value="education">Education</option>
                        <option value="environment">Environment</option>
                        <option value="healthcare">Healthcare</option>
                        <option value="community">Community Service</option>
                    </select>
                </div>

                <div class="filter-group">
                    <label for="location">Location</label>
                    <select id="location">
                        <option value="">All Locations</option>
                        <option value="downtown">Downtown</option>
                        <option value="north">North</option>
                        <option value="south">South</option>
                        <option value="remote">Remote</option>
                    </select>
                </div>

                <div class="filter-group">
                    <label for="availability">Availability</label>
                    <select id="availability">
                        <option value="">Any Time</option>
                        <option value="weekday">Weekdays</option>
                        <option value="weekend">Weekends</option>
                        <option value="evening">Evenings</option>
                    </select>
                </div>

                <div class="filter-group">
                    <label for="duration">Duration</label>
                    <select id="duration">
                        <option value="">Any Duration</option>
                        <option value="oneday">One-time</option>
                        <option value="short">Short-term</option>
                        <option value="long">Long-term</option>
                    </select>
                </div>
            </div>
        </div>

        <div class="results">
            <div class="opportunity-card">
                <h3>Youth Mentoring Program</h3>
                <div class="organization">Local Youth Center</div>
                <div class="tags">
                    <span class="tag">Education</span>
                    <span class="tag">Youth</span>
                    <span class="tag">Long-term</span>
                </div>
                <p>Help guide and support local youth through academic and personal development.</p>
                <div class="card-footer">
                    <span class="location">Downtown</span>
                    <button class="apply-button">Apply Now</button>
                </div>
            </div>

            <div class="opportunity-card">
                <h3>Community Garden Project</h3>
                <div class="organization">Green Earth Initiative</div>
                <div class="tags">
                    <span class="tag">Environment</span>
                    <span class="tag">Outdoors</span>
                    <span class="tag">Weekend</span>
                </div>
                <p>Join us in maintaining and growing our community garden to promote sustainable living.</p>
                <div class="card-footer">
                    <span class="location">North</span>
                    <button class="apply-button">Apply Now</button>
                </div>
            </div>

            <div class="opportunity-card">
                <h3>Senior Care Companion</h3>
                <div class="organization">Elder Care Center</div>
                <div class="tags">
                    <span class="tag">Healthcare</span>
                    <span class="tag">Seniors</span>
                    <span class="tag">Flexible</span>
                </div>
                <p>Provide companionship and support to seniors in our community care facility.</p>
                <div class="card-footer">
                    <span class="location">South</span>
                    <button class="apply-button">Apply Now</button>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
