## Passer des paramètres

    const searchParams = new URLSearchParams();
    searchParams.set('size', 20);
    
    const options = new RequestOptions({ search: searchParams });
    
    http.get(`/api/sessions`, options)
      .subscribe(response => {
        this.domains = response.json();
      });
