function openQuest() {
    document.getElementById('quiz-modal').classList.remove('hidden');
}

function closeQuest() {
    document.getElementById('quiz-modal').classList.add('hidden');
}

function answer(isCorrect) {
    const feedback = document.getElementById('feedback');
    if (isCorrect) {
        feedback.innerText = "Correct! Moving right on the number line increases the value.";
        feedback.style.color = "green";
    } else {
        feedback.innerText = "Not quite! Remember, the further right from Zero Square, the larger the number.";
        feedback.style.color = "red";
    }
}
