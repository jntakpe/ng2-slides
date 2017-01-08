## Paramètre optionnel

    function addPoints(currentScore: number, points?: number): number {
        points = points || 1;
        currentScore += points;
        return currentScore
    }
