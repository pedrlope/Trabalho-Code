import { StyleSheet, Text, TouchableOpacity, View } from "react-native";


const Livraria = ({ descrição }) => {
  return(
    <View style={styles.caixa}>
        <View style={styles.cabeçalho}>
        </View>
        <Text style={styles.descrição}>
            Livro: {Title} = livros
        </Text>
        <View style={styles.cabeçalho}>
        </View>
        <Text style={styles.descrição}>
            Livros abaixo
        </Text>
    </View>
    
  )
}


const styles = StyleSheet.create({
    caixa: {
        backgroundColor: '#fff',
        padding: 15,
        borderRadius: 10,
        shadowColor: '#000',
        shadowOpacity: 0.1,
        shadowRadius: 5,
        elevation: 3,
        marginVertical: 10
    },
    cabeçalho: {
        flex: 1,
        backgroundColor: 'lightred',
        padding: 16
    },
    descrição: {
        fontSize: 16,
        fontWeight: 'bold',
        marginBottom: 8

    },

    caixalivros: {
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
