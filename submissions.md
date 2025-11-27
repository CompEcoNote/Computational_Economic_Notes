---
layout: default
title: Submit Your Paper
permalink: /submission/
---

<div class="submission-page">
    <h1>Submit to Computational Economic Notes</h1>
    
    <div class="submission-options">
        <div class="option-card">
            <h3>📝 Standard Submission</h3>
            <p>Submit your complete paper through our GitHub-based system</p>
            <a href="https://github.com/CompEcoNote/Computational-Economic-Notes/issues/new?template=submission.yml" class="btn btn-primary">Submit via GitHub</a>
        </div>
        
        <div class="option-card">
            <h3>💡 Pre-submission Inquiry</h3>
            <p>Not sure if your paper fits? Start a discussion first</p>
            <a href="https://github.com/CompEcoNote/Computational-Economic-Notes/discussions" class="btn btn-secondary">Start Discussion</a>
        </div>
    </div>

    <h2>Submission Guidelines</h2>
    
    <div class="guidelines">
        <h3>📋 Requirements</h3>
        <ul>
            <li>Open source code (GitHub repository)</li>
            <li>Reproducible computational results</li>
            <li>Clear documentation</li>
            <li>MIT license or similar open license</li>
        </ul>
        
        <h3>⏱️ Process</h3>
        <ul>
            <li><strong>Initial screening:</strong> 1 week</li>
            <li><strong>Peer review:</strong> 2-4 weeks</li>
            <li><strong>Open discussion:</strong> Community feedback</li>
            <li><strong>Final decision:</strong> Editorial review</li>
        </ul>
    </div>

    <div class="cta-section">
        <h2>Ready to Submit?</h2>
        <a href="https://github.com/CompEcoNote/Computational-Economic-Notes/issues/new?template=submission.yml" class="cta-button">
            🚀 Start Submission Process
        </a>
    </div>
</div>

<style>
.submission-options {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 2rem 0;
}

.option-card {
    border: 1px solid #ddd;
    padding: 2rem;
    border-radius: 8px;
    text-align: center;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    margin: 10px 0;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

.btn-primary {
    background: #e74c3c;
    color: white;
}

.btn-secondary {
    background: #3498db;
    color: white;
}

.cta-button {
    display: inline-block;
    background: linear-gradient(135deg, #e74c3c, #c0392b);
    color: white;
    padding: 15px 40px;
    text-decoration: none;
    border-radius: 8px;
    font-size: 1.2em;
    font-weight: bold;
    margin: 2rem 0;
}

.guidelines {
    background: #f8f9fa;
    padding: 2rem;
    border-radius: 8px;
    margin: 2rem 0;
}
</style>
