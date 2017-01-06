## Paramètre optionnel

    function addPoints(currentScore: number, points?: number) {
        points = points || 1;
        currentScore += points;
    }
