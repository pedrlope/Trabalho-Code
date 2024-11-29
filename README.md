import { StyleSheet, Text, TouchableOpacity, View } from "react-native";

const Livraria = ({Descrição}) => {

<View style ={styles.Caixa}>
<View style={styles.Cabeçalho}>
    </View>
<Text style = {styles.Descrição}> 
  Livros abaixo
</Text>
</View>

}

const styles = StyleSheet.create({
    Caixa: {
        backgroundColor: '#fff',
        padding: 15,
        borderRadius: 10,
        shadowColor: '#000',
        shadowOpacity: 0.1,
        shadowRadius: 5,
        elevation: 3,
        marginVertical: 10
    },
    Cabeçalho: {
        flex: 1,
        backgroundColor: 'lightred',
        padding: 16
      },
      Descrição: {
        fontSize: 16,
        fontWeight: 'bold',
        margemBottom: 8
    
    },

    CaixaLivros: {
      backgroundColor: '#fff',
      padding: 15,
      borderRadius: 5,
      shadowColor: '#000',
      shadowOpacity: 0.1,
      shadowRadius: 5,
      elevation: 2,
      marginVertical: 5
  }
})
export default Livraria
